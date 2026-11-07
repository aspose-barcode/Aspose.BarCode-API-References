---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle क्लास"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle क्लास। चार पॉइंट्स का सेट संग्रहीत करता है जो C++ में एक Quadrangle क्षेत्र का प्रतिनिधित्व करता है।"
type: docs
weight: 3000
url: /hi/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


चार [Point](../)s का सेट संग्रहीत करता है जो एक [Quadrangle](./) क्षेत्र का प्रतिनिधित्व करता है।

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | निर्धारित करता है कि निर्दिष्ट [Point](../) इस [Quadrangle](./) क्लास के भीतर शामिल है या नहीं। |
| [Contains](./contains/)(int32_t, int32_t) | निर्धारित करता है कि निर्दिष्ट बिंदु इस [Quadrangle](./) वर्ग के भीतर सम्मिलित है या नहीं। |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | निर्धारित करता है कि निर्दिष्ट [Quadrangle](./) इस [Quadrangle](./) वर्ग में सम्मिलित है या इससे प्रतिच्छेद करता है। |
| [Contains](./contains/)(System::Drawing::Rectangle) | निर्धारित करता है कि निर्दिष्ट [Rectangle](../) इस [Quadrangle](./) वर्ग में सम्मिलित है या इससे प्रतिच्छेद करता है। |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [Quadrangle](./) मान के बराबर है या नहीं। |
| [get_BoundingRectangle](./get_boundingrectangle/)() | इस [Quadrangle](./) को सीमित करने वाला [Rectangle](../) प्राप्त करता है। |
| [get_IsEmpty](./get_isempty/)() | **Tests** यह निर्धारित करता है कि इस [Quadrangle](./) के सभी [Point](../) शून्य मान रखते हैं या नहीं। |
| [get_LeftBottom](./get_leftbottom/)() const | इस [Quadrangle](./) क्षेत्र के बाएँ-निचले कोने का [Point](../) प्राप्त करता है |
| [get_LeftTop](./get_lefttop/)() const | इस [Quadrangle](./) क्षेत्र के बाएँ-ऊपरी कोने का [Point](../) प्राप्त करता है |
| [get_RightBottom](./get_rightbottom/)() const | इस [Quadrangle](./) क्षेत्र के दाएँ-निचले कोने का [Point](../) प्राप्त करता है |
| [get_RightTop](./get_righttop/)() const | इस [Quadrangle](./) क्षेत्र के दाएँ-ऊपरी कोने का [Point](../) प्राप्त करता है |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [Quadrangle](./quadrangle/)() | नए खाली [Quadrangle](./) वर्ग का एक उदाहरण आरंभ करता है। |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | वर्णनात्मक बिंदुओं के साथ नए [Quadrangle](./) वर्ग का एक उदाहरण आरंभ करता है। |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | इस [Quadrangle](./) क्षेत्र के बाएँ-निचले कोने का [Point](../) प्राप्त करता है |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | इस [Quadrangle](./) क्षेत्र के बाएँ-ऊपरी कोने का [Point](../) प्राप्त करता है |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | इस [Quadrangle](./) क्षेत्र के दाएँ-निचले कोने का [Point](../) प्राप्त करता है |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | इस [Quadrangle](./) क्षेत्र के दाएँ-ऊपरी कोने का [Point](../) प्राप्त करता है |
| [ToString](./tostring/)() const override | इस [Quadrangle](./) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Empty](./empty/) | एक [Quadrangle](./) वर्ग का प्रतिनिधित्व करता है जिसमें इसकी गुणधर्म अनिर्दिष्ट छोड़ दिए गए हैं। |
## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
