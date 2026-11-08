---
title: "Aspose::BarCode::Generation::SymbologyEncodeType sınıfı"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::SymbologyEncodeType sınıfı. Semboloji kodlama türü. C++'da örnek almak için EncodeTypes'a bakın."
type: docs
weight: 4900
url: /tr/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Semboloji kodlama türü. Örnek almak için [EncodeTypes](../encodetypes/) adresine bakın.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Bu örneğin belirtilen bir [BaseEncodeType](../baseencodetype/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_Classification](../baseencodetype/get_classification/)() const | Bu sembolojinin sınıflandırmasını alır. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Kodlama türünün dizinini alır |
| [get_TypeName](../baseencodetype/get_typename/)() const | Kodlama türünün adını alır |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetString](../baseencodetype/getstring/)() | [BaseEncodeType](../baseencodetype/) örneğini eşdeğer dize temsiline dönüştürür. Dize formatı: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](../baseencodetype/) örneğini eşdeğer dize temsiline dönüştürür. Dize formatı: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | [BaseEncodeType](../baseencodetype/) adının dize temsilini örneğine dönüştürür. |
| [ToString](../baseencodetype/tostring/)() const override | Verilen [BaseEncodeType](../baseencodetype/) adını dize olarak döndürür. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |
## Açıklamalar


Bu örnek, [SymbologyEncodeType](./) sınıfının bir örneğinin nasıl alınacağını gösterir.
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Ayrıca Bakınız

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
