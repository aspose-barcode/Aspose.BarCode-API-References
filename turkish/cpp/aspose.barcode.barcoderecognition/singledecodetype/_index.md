---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType sınıfı"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType sınıfı. Tek çözümleme türü. C++'ta örnek almak için decode type bölümüne bakın."
type: docs
weight: 3200
url: /tr/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Tek decode type. Örneği almak için decode type'a bakın.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Bu örneğin belirtilen listeye dahil olup olmadığını gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Bu örneğin belirtilen bir [SingleDecodeType](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Belirtilen [MultiDecodeType](../multidecodetype/) koleksiyonunun yalnızca bu çözümleme türünü içerip içermediğini gösteren bir değer döndürür. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen bir [SingleDecodeType](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Bu örneğin belirtilen bir [BaseDecodeType](../basedecodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_TypeIndex](./get_typeindex/)() const | Çözümleme türünün bir indeksini alır |
| [get_TypeName](./get_typename/)() const | Çözümleme türünün adını alır |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetString](./getstring/)() | [SingleDecodeType](./) örneğini eşdeğer dize temsiline dönüştürür. Dize biçimi: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](./) örneğini eşdeğer dize temsiline dönüştürür. Dize biçimi: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | [SingleDecodeType](./) adının dize temsiliğini örneğine dönüştürür. |
| [ToString](./tostring/)() const override | Verilen [SingleDecodeType](./) adını dize olarak döndürür. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](./) dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) dize temsiliğini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) dize temsiliğini somut tür belirlenerek örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Açıklamalar


Bu örnek, tek çözümleme türünün örneğini nasıl alacağınızı gösterir.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Ayrıca Bakınız

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
