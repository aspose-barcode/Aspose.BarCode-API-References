---
title: "enum"
linktitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Kodningsläge för MaxiCode-streckkoder i C++."
type: docs
weight: 7500
url: /sv/cpp/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enum


Kodningsläge för MaxiCode-streckkoder.

```cpp
enum class MaxiCodeEncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | I Auto‑läge kodas CodeText med maximal datakomprimering. Unicode‑tecken omkodas i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. |
| Utökad | 3 |  |
| Binär | 4 | I Binär‑läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | 5 | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |

## Anmärkningar



```cpp
[C#]
//Auto‑läge
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Byte‑läge
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Utökad kodtextläge
//skapa kodtext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
