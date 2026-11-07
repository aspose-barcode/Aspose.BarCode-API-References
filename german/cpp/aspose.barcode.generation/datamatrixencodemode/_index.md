---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Der Codierungsmodus des DataMatrix-Encoders, standardmäßig Auto in C++."
type: docs
weight: 6300
url: /de/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Kodierungsmodus des DataMatrix-Encoders, standardmäßig Auto

```cpp
enum class DataMatrixEncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| ASCII | 1 | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte |
| C40 | 8 | Verwendet C40-Kodierung. Kodiert Großbuchstaben alphanumerisch, Kleinbuchstaben und Sonderzeichen |
| Text | 9 | Verwendet Textkodierung. Kodiert Kleinbuchstaben alphanumerisch, Großbuchstaben und Sonderzeichen |
| EDIFACT | 10 | Verwendet EDIFACT-Kodierung. Verwendet sechs Bits pro Zeichen, kodiert Ziffern, Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben. |
| ANSIX12 | 11 | Verwendet ANSI X12-Kodierung. |
| Erweitert | 13 |  |
| Base256 | 14 | Kodiert 8-Bit-Werte |
| Binär | 15 | Im Binärmodus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | 16 | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |

## Hinweise


Dieses Beispiel zeigt, wie man Codetext im erweiterten Modus verwendet.
```cpp
[C#]
//Auto-Modus
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Byte-Modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Erweiterter Codetext-Modus
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

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
