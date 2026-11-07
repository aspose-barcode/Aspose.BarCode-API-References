---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::ITFParameters Klasse. ITF-Parameter in C++."
type: docs
weight: 3300
url: /de/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF-Parameter.

```cpp
class ITFParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Ruft die Dicke einer ITF-Grenze (Bearer Bar) in [Unit](../unit/)-Wert ab. Standardwert: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Grenztyp des ITF-Barcodes. Standardwert: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Größe der Ruhebereiche in xDimension. Standardwert: 10, d.h. wenn xDimension = 2px, dann betragen die Ruhebereiche 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Setzt die Dicke einer ITF-Grenze (Bearer Bar) in [Unit](../unit/)-Wert. Standardwert: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Grenztyp des ITF-Barcodes. Standardwert: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Größe der Ruhebereiche in xDimension. Standardwert: 10, d.h. wenn xDimension = 2px, dann betragen die Ruhebereiche 20px. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [ITFParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
