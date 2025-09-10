---
title: Aspose::BarCode::Generation::ITFParameters class
linktitle: ITFParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::ITFParameters class. ITF parameters in C++.'
type: docs
weight: 3000
url: /cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF parameters.

```cpp
class ITFParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ItfBorderThickness](./get_itfborderthickness/)() const | Gets an ITF border (bearer bar) thickness in [Unit](../unit/) value. Default value: 12pt. |
| [get_ItfBorderType](./get_itfbordertype/)() const | Border type of ITF barcode. Default value: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() | Size of the quiet zones in xDimension. Default value: 10, meaning if xDimension = 2px than quiet zones will be 20px. |
| [set_ItfBorderThickness](./set_itfborderthickness/)(System::SharedPtr\<Unit\>) | Sets an ITF border (bearer bar) thickness in [Unit](../unit/) value. Default value: 12pt. |
| [set_ItfBorderType](./set_itfbordertype/)(ITF14BorderType) | Border type of ITF barcode. Default value: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Size of the quiet zones in xDimension. Default value: 10, meaning if xDimension = 2px than quiet zones will be 20px. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [ITFParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
