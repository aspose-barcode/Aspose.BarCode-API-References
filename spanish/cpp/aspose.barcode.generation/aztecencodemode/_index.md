---
title: "enum"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Modo de codificación para códigos Aztec en C++."
type: docs
weight: 5300
url: /es/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Modo de codificación para códigos de barras Aztec.

```cpp
enum class AztecEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se vuelven a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| Extendido | 3 |  |
| Binario | 4 | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | 5 | En modo ECI, todo el mensaje se vuelve a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |

## Observaciones



```cpp
[C#]
//Modo Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Modo extendido
//crear texto de código
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar texto de código
string codetext = textBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
