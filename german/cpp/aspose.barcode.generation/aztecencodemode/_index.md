---
title: "enum"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Kodierungsmodus für Aztec-Barcodes in C++."
type: docs
weight: 5300
url: /de/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Kodierungsmodus für Aztec-Barcodes.

```cpp
enum class AztecEncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. |
| Erweitert | 3 |  |
| Binär | 4 | Im Binärmodus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | 5 | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding neu kodiert, wobei ein ECI-Identifikator eingefügt wird. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Codierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |

## Hinweise



```cpp
[C#]
//Auto-Modus
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

//Erweiterter Modus
//Codetext erstellen
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
