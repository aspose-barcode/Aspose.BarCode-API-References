---
title: "Enum AztecEncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enum Aspose.BarCode.Generation.AztecEncodeMode. Modo de codificación para códigos de barras Aztec"
type: docs
weight: 940
url: /es/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Modo de codificación para códigos de barras Aztec.

```csharp
public enum AztecEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| Extended | `3` | Modo extendido que admite varios modos ECI. |
| Binary | `4` | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | `5` | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no soportar este modo. |

## Ejemplos

```csharp
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

//Modo Extendido
//crear codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


