---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::DotCodeParameters class. DotCode‑parametrar i C++."
type: docs
weight: 2200
url: /sv/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Parametrar för DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [get_Columns](./get_columns/)() const | Identifierar kolumnantal. Summan av antalet rader plus antalet kolumner i en DotCode‑symbol måste vara udda. Antalet kolumner måste vara minst 5. Standardvärde: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifierar ECI‑kodning. Används när DotCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identifierar DotCode‑kodningsläge. Standardvärde: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [get_Rows](./get_rows/)() const | Identifierar radantal. Summan av antalet rader plus antalet kolumner i en DotCode‑symbol måste vara udda. Antalet rader måste vara minst 5. Standardvärde: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identifierar ID‑t för DotCode‑structured‑append‑läge‑streckkoden. ID börjar på 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identifierar antalet streckkoder i DotCode‑structured‑append‑läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [set_Columns](./set_columns/)(int32_t) | Identifierar kolumnantal. Summan av antalet rader plus antalet kolumner i en DotCode‑symbol måste vara udda. Antalet kolumner måste vara minst 5. Standardvärde: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifierar ECI‑kodning. Används när DotCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Identifierar DotCode‑kodningsläge. Standardvärde: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [set_Rows](./set_rows/)(int32_t) | Identifierar radantal. Summan av antalet rader plus antalet kolumner i en DotCode‑symbol måste vara udda. Antalet rader måste vara minst 5. Standardvärde: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identifierar ID‑t för DotCode‑structured‑append‑läge‑streckkoden. ID börjar på 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identifierar antalet streckkoder i DotCode‑structured‑append‑läge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [DotCodeParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
