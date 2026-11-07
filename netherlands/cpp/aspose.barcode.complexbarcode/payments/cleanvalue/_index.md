---
title: "methode"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Reinigt een stringwaarde om deze geschikt te maken voor de Swiss Payment Standards 2018 in C++."
type: docs
weight: 100
url: /nl/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Reinigt een tekenreekswaarde om deze bruikbaar te maken voor de Zwitserse betalingsnormen 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | System::String | De te reinigen stringwaarde. |
| result | Payments::CleaningResult\& | Het resultaat dat moet worden gevuld met de gereinigde string en vlag. |
## Opmerkingen


Niet-ondersteunde tekens(volgens Swiss Payment Standards 2018, ch. 2.4.1 en bijlage D) worden vervangen door spaties(niet-ondersteunde witruimte) of punten (alle andere niet-ondersteunde tekens). Voorloop- en naloopwitruimte wordt verwijderd.

Als tekens boven 0xff worden gedetecteerd, wordt de string eerst genormaliseerd zodat letters met umlauts of accenten die met twee codepunten worden weergegeven, worden samengevoegd tot één codepunt(indien mogelijk), waarvan sommige geldig kunnen worden.

Als de resulterende string alleen witruimte bevat, **null** wordt geretourneerd.

## Zie ook

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
