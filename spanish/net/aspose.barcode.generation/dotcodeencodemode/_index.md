---
title: "Enumeración DotCodeEncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.Generation.DotCodeEncodeMode. Modo de codificación para códigos de barras DotCode"
type: docs
weight: 1240
url: /es/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Modo de codificación para códigos de barras DotCode.

```csharp
public enum DotCodeEncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se re‑codifican en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| Binary | `3` | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | `4` | En modo ECI, todo el mensaje se re‑codifica en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no soportar este modo. |
| Extended | `5` | Modo extendido que admite varios modos ECI. |

## Ejemplos

```csharp
[C#]
//Modo automático con macros
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Modo Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Modo Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Modo codetext Extendido
//crear codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generar codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generar
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


