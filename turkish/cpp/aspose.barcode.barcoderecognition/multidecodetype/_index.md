---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType sınıfı"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType sınıfı. C++'da birleşik çözümleme türü."
type: docs
weight: 2600
url: /tr/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Bileşik çözümleme türü.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Bir tane daha [SingleDecodeType](../singledecodetype/) öğesini [MultiDecodeType](./) öğesine ekler. |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Barkod türlerinden tüm tipleri içerip içermediğini kontrol eder. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Herhangi bir tür içeriyor mu |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Bu örneğin belirtilen bir [MultiDecodeType](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Bu çözümleme türleri koleksiyonunun yalnızca belirtilen [SingleDecodeType](../singledecodetype/) değerini içerip içermediğini gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen bir [MultiDecodeType](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Bu örneğin belirtilen bir [BaseDecodeType](../basedecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](../singledecodetype/) öğesini [MultiDecodeType](./) öğesinden çıkarır ve yeni bir [MultiDecodeType](./) örneği döndürür. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Tek tiplerin sayısını döndürür. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetSingleTypes](./getsingletypes/)() | Tek tiplerin bir listesini temsil eder. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [MultiDecodeType](./) sınıfının yeni bir örneğini başlatır. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [MultiDecodeType](./) sınıfının yeni bir örneğini başlatır. |
| [ToString](./tostring/)() const override | [MultiDecodeType](./) öğesini dize olarak temsil eden geçersiz kılınmış yöntem. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](./) öğesinin dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/) öğesinin dize temsilini örneğine dönüştürür. Döndürülen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) dize temsiliğini somut tür belirlenerek örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Açıklamalar


Bu örnek, [SingleDecodeType](../singledecodetype/) ve MultiDecode türlerini birleştiren birleşik MultiDecode türlerinin nasıl oluşturulacağını gösterir.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## Ayrıca Bakınız

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
