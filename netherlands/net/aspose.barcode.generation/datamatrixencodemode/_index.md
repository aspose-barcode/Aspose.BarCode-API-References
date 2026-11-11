---
title: "Enum DataMatrixEncodeMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. De coderingsmodus van DataMatrix-encoders is standaard Auto."
type: docs
weight: 1200
url: /nl/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Coderingsmodus van de DataMatrix-encoder, standaard Auto

```csharp
public enum DataMatrixEncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| ASCII | `1` | Codeert één alfanumeriek of twee numerieke tekens per byte. |
| C40 | `8` | Gebruikt C40-codering. Codeert hoofdletter alfanumeriek, kleine letters en speciale tekens. |
| Text | `9` | Gebruikt Text-codering. Codeert kleine letters alfanumeriek, hoofdletters en speciale tekens. |
| EDIFACT | `10` | Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers, hoofdletters en vele leestekens, maar ondersteunt geen kleine letters. |
| ANSIX12 | `11` | Gebruikt ANSI X12-codering. |
| Extended | `13` | ExtendedCodetext-modus maakt handmatig schakelen tussen coderingsschema's en ECI-coderingen in codetext mogelijk. |
| Base256 | `14` | Codeer 8‑bit waarden. |
| Binary | `15` | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | `16` | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |

## Voorbeelden

Dit voorbeeld toont hoe codetext in Extended-modus te gebruiken.

```csharp
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


//Extended codetext-modus
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

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


