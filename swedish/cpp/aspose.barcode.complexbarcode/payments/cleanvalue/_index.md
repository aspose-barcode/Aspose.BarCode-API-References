---
title: "metod"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Rensar ett strängvärde för att göra det användbart enligt Swiss Payment Standards 2018 i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Rensar ett strängvärde för att göra det giltigt för de schweiziska betalningsstandarderna 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::String | Strängvärdet att rensa. |
| resultat | Payments::CleaningResult\& | Resultatet som ska fyllas med den rensade strängen och flaggan. |
## Anmärkningar


Ej stödda tecken(enligt Swiss Payment Standards 2018, kap. 2.4.1 och bilaga D) ersätts med mellanslag(ej stödd blanksteg) eller punkter (alla andra ej stödda tecken). Inledande och avslutande blanksteg tas bort.

Om tecken utöver 0xff upptäcks normaliseras strängen först så att bokstäver med umlaut eller accenter som uttrycks med två kodpunkter slås ihop till en enda kodpunkt (om möjligt), varav vissa kan bli giltiga.

Om den resulterande strängen är enbart blanksteg, returneras **null**.

## Se även

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
