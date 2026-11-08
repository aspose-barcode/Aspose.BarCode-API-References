---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. DataMatrix kodarens kodningsläge, standard är Auto i C++."
type: docs
weight: 6300
url: /sv/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix-kodares kodningsläge, standard är Auto

```cpp
enum class DataMatrixEncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | I Auto‑läge kodas CodeText med maximal datakomprimering. Unicode‑tecken omkodas i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. |
| ASCII | 1 | Kodar ett alfanumeriskt eller två numeriska tecken per byte |
| C40 | 8 | Använder C40‑kodning. Kodar versala alfanumeriska, gemena och specialtecken |
| Text | 9 | Använder Text‑kodning. Kodar gemena alfanumeriska, versala och specialtecken |
| EDIFACT | 10 | Använder EDIFACT‑kodning. Använder sex bitar per tecken, kodar siffror, versala bokstäver och många skiljetecken, men har ingen stöd för gemena bokstäver. |
| ANSIX12 | 11 | Använder ANSI X12‑kodning. |
| Utökad | 13 |  |
| Base256 | 14 | Koda 8‑bitarsvärden |
| Binär | 15 | I Binär‑läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | 16 | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |

## Anmärkningar


Detta exempel visar hur man gör kodtext i Utökat läge.
```cpp
[C#]
//Auto‑läge
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Byte‑läge
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Utökad kodtextläge
//skapa kodtext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
