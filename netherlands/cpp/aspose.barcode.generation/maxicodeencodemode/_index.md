---
title: "enum"
linktitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Coderingmodus voor MaxiCode-barcodes in C++."
type: docs
weight: 7500
url: /nl/cpp/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enum


Coderingsmodus voor MaxiCode barcodes.

```cpp
enum class MaxiCodeEncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. |
| Extended | 3 |  |
| Binary | 4 | In de Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | 5 | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |

## Opmerkingen



```cpp
[C#]
//Auto-modus
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes-modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Uitgebreide codetext-modus
//codetext maken
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
