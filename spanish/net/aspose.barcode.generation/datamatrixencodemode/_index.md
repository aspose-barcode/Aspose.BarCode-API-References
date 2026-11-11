---
title: "Enumeración DataMatrixEncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. El modo de codificación de los codificadores DataMatrix es por defecto Auto"
type: docs
weight: 1200
url: /es/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Modo de codificación del codificador DataMatrix, por defecto Auto

```csharp
public enum DataMatrixEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| ASCII | `1` | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
| C40 | `8` | Utiliza codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales |
| Text | `9` | Utiliza codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales |
| EDIFACT | `10` | Utiliza codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas. |
| ANSIX12 | `11` | Utiliza codificación ANSI X12. |
| Extended | `13` | El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación y las codificaciones ECI en el codetext. |
| Base256 | `14` | Codificar valores de 8 bits |
| Binary | `15` | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | `16` | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no soportar este modo. |

## Ejemplos

Este ejemplo muestra cómo crear codetext en Modo Extendido.

```csharp
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


//Modo codetext Extendido
//crear codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


