---
title: "Enum DataMatrixEncodeMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. Der Kodierungsmodus der DataMatrix-Encoder ist standardmäßig Auto."
type: docs
weight: 1200
url: /de/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Kodierungsmodus des DataMatrix-Encoders, standardmäßig Auto

```csharp
public enum DataMatrixEncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| ASCII | `1` | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte. |
| C40 | `8` | Verwendet C40-Kodierung. Kodiert Großbuchstaben-Alphanumerik, Kleinbuchstaben und Sonderzeichen. |
| Text | `9` | Verwendet Text-Kodierung. Kodiert Kleinbuchstaben-Alphanumerik, Großbuchstaben und Sonderzeichen. |
| EDIFACT | `10` | Verwendet EDIFACT-Kodierung. Nutzt sechs Bits pro Zeichen, kodiert Ziffern, Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben. |
| ANSIX12 | `11` | Verwendet ANSI-X12-Kodierung. |
| Extended | `13` | Der ExtendedCodetext-Modus ermöglicht das manuelle Umschalten von Kodierungsschemata und ECI-Kodierungen im Codetext. |
| Base256 | `14` | Kodiert 8-Bit-Werte. |
| Binary | `15` | Im Binär-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | `16` | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |

## Beispiele

Dieses Beispiel zeigt, wie man Codetext im Extended-Modus erstellt.

```csharp
[C#]
//Auto-Modus
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes-Modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Extended-Codetext-Modus
//Codetext erstellen
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();    

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


