---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. De coderingsmodus van de DataMatrix-encoder, standaard Auto in C++."
type: docs
weight: 6300
url: /nl/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Coderingsmodus van de DataMatrix-encoder, standaard Auto

```cpp
enum class DataMatrixEncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| ASCII | 1 | Codeert één alfanumeriek of twee numerieke tekens per byte |
| C40 | 8 | Gebruikt C40-codering. Codeert hoofdletter‑alfanumeriek, kleine letters en speciale tekens |
| Tekst | 9 | Gebruikt Tekst‑codering. Codeert kleine letters alfanumeriek, hoofdletters en speciale tekens |
| EDIFACT | 10 | Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers, hoofdletters en vele interpunctietekens, maar ondersteunt geen kleine letters. |
| ANSIX12 | 11 | Gebruikt ANSI X12-codering. |
| Extended | 13 |  |
| Base256 | 14 | Codeer 8‑bit waarden |
| Binary | 15 | In de Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | 16 | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |

## Opmerkingen


Deze voorbeeld toont hoe je codetext in de Extended-modus doet.
```cpp
[C#]
//Auto-modus
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes-modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Uitgebreide codetext-modus
//codetext maken
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
