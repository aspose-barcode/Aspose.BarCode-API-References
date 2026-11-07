---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::ITFParameters class. Parameter ITF dalam C++."
type: docs
weight: 3300
url: /id/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Parameter ITF.

```cpp
class ITFParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Mendapatkan ketebalan batas ITF (bearer bar) dalam nilai [Unit](../unit/). Nilai default: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Tipe batas barcode ITF. Nilai default: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Ukuran zona tenang dalam xDimension. Nilai default: 10, yang berarti jika xDimension = 2px maka zona tenang akan menjadi 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Mengatur ketebalan batas ITF (bearer bar) dalam nilai [Unit](../unit/). Nilai default: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Tipe batas barcode ITF. Nilai default: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Ukuran zona tenang dalam xDimension. Nilai default: 10, yang berarti jika xDimension = 2px maka zona tenang akan menjadi 20px. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [ITFParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
