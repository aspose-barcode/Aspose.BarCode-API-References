---
title: "Enum DotCodeEncodeMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.DotCodeEncodeMode Enum. Kodierungsmodus für DotCode-Strichcodes"
type: docs
weight: 1240
url: /de/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Kodierungsmodus für DotCode-Barcodes.

```csharp
public enum DotCodeEncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| Binary | `3` | Im Binär-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | `4` | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| Extended | `5` | Erweiterter Modus, der mehrere ECI‑Modi unterstützt. |

## Beispiele

```csharp
[C#]
//Automatischer Modus mit Makros
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Auto-Modus
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes-Modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended-Codetext-Modus
//Codetext erstellen
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();    

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


