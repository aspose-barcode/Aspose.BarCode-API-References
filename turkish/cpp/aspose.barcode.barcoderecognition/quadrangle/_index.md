---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle sınıfı"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle sınıfı. C++'da bir Quadrangle bölgesini temsil eden dört Point kümesini depolar."
type: docs
weight: 3000
url: /tr/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Bir [Quadrangle](./) bölgesini temsil eden dört [Point](../) kümesini depolar.

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Belirtilen [Point](../) öğesinin bu [Quadrangle](./) sınıfı içinde bulunup bulunmadığını belirler. |
| [Contains](./contains/)(int32_t, int32_t) | Belirtilen noktanın bu [Quadrangle](./) sınıfı içinde bulunup bulunmadığını belirler. |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Belirtilen [Quadrangle](./) nesnesinin bu [Quadrangle](./) sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler. |
| [Contains](./contains/)(System::Drawing::Rectangle) | Belirtilen [Rectangle](../) nesnesinin bu [Quadrangle](./) sınıfı içinde bulunup bulunmadığını veya kesişip kesişmediğini belirler. |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Bu örneğin belirtilen bir [Quadrangle](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Bu [Quadrangle](./) sınıfını sınırlayan [Rectangle](../) nesnesini alır. |
| [get_IsEmpty](./get_isempty/)() | **Tests** bu [Quadrangle](./) sınıfının tüm [Point](../) noktalarının sıfır değerine sahip olup olmadığını test eder. |
| [get_LeftBottom](./get_leftbottom/)() const | [Quadrangle](./) bölgesinin sol-alt köşe [Point](../) noktasını alır. |
| [get_LeftTop](./get_lefttop/)() const | [Quadrangle](./) bölgesinin sol-üst köşe [Point](../) noktasını alır. |
| [get_RightBottom](./get_rightbottom/)() const | [Quadrangle](./) bölgesinin sağ-alt köşe [Point](../) noktasını alır. |
| [get_RightTop](./get_righttop/)() const | [Quadrangle](./) bölgesinin sağ-üst köşe [Point](../) noktasını alır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [Quadrangle](./quadrangle/)() | [Quadrangle](./) sınıfının yeni boş bir örneğini başlatır. |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | [Quadrangle](./) sınıfının tanımlayıcı noktalarla yeni bir örneğini başlatır. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | [Quadrangle](./) bölgesinin sol-alt köşe [Point](../) noktasını alır. |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | [Quadrangle](./) bölgesinin sol-üst köşe [Point](../) noktasını alır. |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | [Quadrangle](./) bölgesinin sağ-alt köşe [Point](../) noktasını alır. |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | [Quadrangle](./) bölgesinin sağ-üst köşe [Point](../) noktasını alır. |
| [ToString](./tostring/)() const override | Bu [Quadrangle](./) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Özellikleri başlatılmamış bir [Quadrangle](./) sınıfını temsil eder. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
