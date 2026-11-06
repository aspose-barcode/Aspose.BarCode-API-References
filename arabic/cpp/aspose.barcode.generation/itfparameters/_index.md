---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::ITFParameters class. معلمات ITF في C++."
type: docs
weight: 3300
url: /ar/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


معلمات ITF.

```cpp
class ITFParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | يحصل على سمك حد ITF (شريط حامل) بوحدة [Unit](../unit/). القيمة الافتراضية: 12pt. |
| [get_BorderType](./get_bordertype/)() const | نوع حد الباركود ITF. القيمة الافتراضية: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | يضبط سماكة حد ITF (شريط الحامل) بوحدة [Unit](../unit/). القيمة الافتراضية: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | نوع حد الباركود ITF. القيمة الافتراضية: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px. |
| [ToString](./tostring/)() const override | يعيد تمثيلًا نصيًا قابلًا للقراءة لهذا [ITFParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
