---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::ITFParameters-klass. ITF-parametrar i C++."
type: docs
weight: 3300
url: /sv/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Parametrar för ITF.

```cpp
class ITFParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Hämtar en ITF‑kant (bärare‑stapel) tjocklek i [Unit](../unit/) värde. Standardvärde: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Kanttyp för ITF‑streckkod. Standardvärde: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Storlek på de tysta zonerna i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir de tysta zonerna 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Ställer in en ITF‑kant (bärare‑stapel) tjocklek i [Unit](../unit/) värde. Standardvärde: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Kanttyp för ITF‑streckkod. Standardvärde: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Storlek på de tysta zonerna i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir de tysta zonerna 20px. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [ITFParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
