---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType sınıfı"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType sınıfı. C++'ta MultiDecodeType ve SingleDecodeType için temel sınıf."
type: docs
weight: 900
url: /tr/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


[MultiDecodeType](../multidecodetype/) ve [SingleDecodeType](../singledecodetype/) için temel sınıf.

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Verilen çözümleme türlerinden herhangi birinin dahil olup olmadığını belirler |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Bu örneğin belirtilen bir [SingleDecodeType](../singledecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Bu örneğin belirtilen bir [MultiDecodeType](../multidecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Belirtilen [BaseDecodeType](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) öğesinin dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](./) öğesinin dize temsilini somut tür belirlenerek örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Açıklamalar


Bu örnek, [BaseDecodeType](./) öğesinin [SingleDecodeType](../singledecodetype/) ve [MultiDecodeType](../multidecodetype/) ile nasıl kullanılacağını gösterir.
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
