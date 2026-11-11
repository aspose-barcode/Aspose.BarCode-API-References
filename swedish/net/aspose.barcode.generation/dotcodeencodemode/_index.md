---
title: "Enum DotCodeEncodeMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.DotCodeEncodeMode-enum. Kodningsläge för DotCode-streckkoder"
type: docs
weight: 1240
url: /sv/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Kodningsläge för DotCode-streckkoder.

```csharp
public enum DotCodeEncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | I Auto-läge kodas CodeText med maximal datakomprimering. Unicode-tecken kodas om i den angivna ECIEncoding‑kodningen med införandet av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. |
| Binary | `3` | I Binärt läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | `4` | I ECI‑läge kodas hela meddelandet om i den angivna ECIEncoding‑kodningen med införandet av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |
| Extended | `5` | Utökat läge som stödjer flera ECI‑lägen. |

## Exempel

```csharp
[C#]
//Automatiskt läge med makron
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Auto-läge
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Byte‑läge
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended kodtextläge
//skapa kodtext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();    

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Se även

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


