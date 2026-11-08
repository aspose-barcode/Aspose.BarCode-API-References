---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "enum. Modo de codificación del codificador DataMatrix, por defecto Auto en C++."
type: docs
weight: 6300
url: /es/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Modo de codificación del codificador DataMatrix, por defecto Auto

```cpp
enum class DataMatrixEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se vuelven a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| ASCII | 1 | Codifica un carácter alfanumérico o dos caracteres numéricos por byte. |
| C40 | 8 | Utiliza codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales. |
| Texto | 9 | Utiliza codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales. |
| EDIFACT | 10 | Utiliza codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas. |
| ANSIX12 | 11 | Utiliza codificación ANSI X12. |
| Extendido | 13 |  |
| Base256 | 14 | Codificar valores de 8 bits |
| Binario | 15 | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | 16 | En modo ECI, todo el mensaje se vuelve a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |

## Observaciones


Este ejemplo muestra cómo realizar codetext en modo Extendido.
```cpp
[C#]
//Modo Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Modo Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Modo de texto de código extendido
//crear texto de código
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generar texto de código
string codetext = textBuilder.GetExtendedCodetext();

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
