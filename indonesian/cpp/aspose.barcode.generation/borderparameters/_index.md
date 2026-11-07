---
title: "Aspose::BarCode::Generation::BorderParameters kelas"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::BorderParameters kelas. Parameter batas gambar kode batang dalam C++."
type: docs
weight: 800
url: /id/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Parameter batas gambar barcode

```cpp
class BorderParameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Color](./get_color/)() const | Warna batas. Nilai default: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Gaya dash batas. Nilai default: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Visibilitas batas. Jika false maka parameter Width selalu diabaikan (0). Nilai default: false. |
| [get_Width](./get_width/)() const | Lebar batas. Nilai default: 0. Diabaikan jika Visible diatur ke false. |
| [set_Color](./set_color/)(System::Drawing::Color) | Warna batas. Nilai default: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Gaya dash batas. Nilai default: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Visibilitas batas. Jika false maka parameter Width selalu diabaikan (0). Nilai default: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Lebar batas. Nilai default: 0. Diabaikan jika Visible diatur ke false. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [BorderParameters](./). |
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
