---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext sınıfı"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext sınıfı. GS1 kod metnini, Uygulama Tanımlayıcısı öğelerinin sıralı bir dizisi olarak kodlamak ve kod çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Parantezli gösterim (AI)değer(AI)değer biçimindedir. Bir değer içindeki gerçek açma parantez ''('' '' ('' olarak yazılmalıdır; bu tek desteklenen kaçış dizisidir. Bir değer içindeki kapanış parantez '')'' C++'da kaçış gerektirmez."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


GS1 kod metnini, Uygulama Tanımlayıcı öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Köşeli gösterim (AI)değer(AI)değer biçimindedir. Bir değerin içinde bulunan gerçek açılış parantezi '(' '(;' olarak yazılmalıdır; bu tek desteklenen kaçış dizisidir. Bir değerin içinde bulunan kapanış parantezi ')' kaçış gerektirmez.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Doğrulanmış bir Uygulama Tanımlayıcı öğesi ekler. |
| [get_BarcodeType](./get_barcodetype/)() const | Bu GS1 kod metnini kodlamak için kullanılan barkod tipini alır. Desteklenen tipler GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR ve GS1 DataBar tipleridir. Varsayılan değer GS1Code128'dir. |
| [get_Count](./get_count/)() | Uygulama Tanımlayıcı öğelerinin sayısını alır. |
| [get_Elements](./get_elements/)() | Kaynak sırasındaki tüm öğelerin bir kopyasını alır. |
| [GetAll](./getall/)(System::String) | Bir Uygulama Tanımlayıcısı için tüm değerleri kaynak sırasıyla alır. |
| [GetBarcodeType](./getbarcodetype/)() override | Bu GS1 kod metnini kodlamak için kullanılan barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Parantezli GS1 kod metnini (AI)değer(AI)değer biçiminde oluşturur. Değerlerdeki gerçek açma parantezler ( olarak kaçış yapılır. |
| [GetFirst](./getfirst/)(System::String) | Bir Uygulama Tanımlayıcısı için ilk değeri alır. |
| [GS1Codetext](./gs1codetext/)() | Boş bir GS1 kod metni başlatır. |
| [idx_get](./idx_get/)(int32_t) | Sıralı dizideki konumuna göre bir öğeyi alır. |
| [InitFromString](./initfromstring/)(System::String) override | Bu örneği (AI)değer(AI)değer biçimindeki parantezli GS1 kod metninden başlatır. Mevcut öğeler, sağlanan kod metni başarıyla ayrıştırıldıktan sonra yalnızca değiştirilir. |
| static [Parse](./parse/)(System::String) | Parantezli bir GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırır. Bir değer içinde gerçek '(' '(' olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Bu GS1 kod metnini kodlamak için kullanılan barkod tipini ayarlar. Desteklenen tipler GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR ve GS1 DataBar tipleridir. Varsayılan değer GS1Code128'dir. |
| [ToString](./tostring/)() const override | Parantezli GS1 temsilini (AI)değer(AI)değer biçiminde döndürür. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Parantezli bir GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür. Bir değerin içinde görülen '(' karakteri (; olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| static [Validate](./validate/)(System::String) | Parantezli bir GS1 öğe dizesini (AI)değer(AI)değer biçiminde nesne oluşturmadan doğrular. Bir değerin içinde görülen '(' karakteri (; olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
