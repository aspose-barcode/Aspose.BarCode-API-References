---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::ITFParameters sınıfı. C++'de ITF parametreleri."
type: docs
weight: 3300
url: /tr/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


ITF parametreleri.

```cpp
class ITFParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | [Unit](../unit/) biriminde bir ITF kenar (taşıyıcı çubuk) kalınlığını alır. Varsayılan değer: 12pt. |
| [get_BorderType](./get_bordertype/)() const | ITF barkodunun kenar tipi. Varsayılan değer: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | xDimension'daki sessiz bölgelerin boyutu. Varsayılan değer: 10, yani xDimension = 2px ise sessiz bölgeler 20px olur. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | ITF kenar (taşıyıcı çubuk) kalınlığını [Unit](../unit/) biriminde ayarlar. Varsayılan değer: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | ITF barkodunun kenar tipi. Varsayılan değer: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | xDimension'daki sessiz bölgelerin boyutu. Varsayılan değer: 10, yani xDimension = 2px ise sessiz bölgeler 20px olur. |
| [ToString](./tostring/)() const override | Bu [ITFParameters](./) öğesinin insan tarafından okunabilir dize temsilini döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
