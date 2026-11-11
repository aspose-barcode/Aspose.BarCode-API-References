---
title: "Sınıf GS1Codetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext sınıfı. GS1 codetext'i, Application Identifier öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Application Identifier'lar korunur. Köşeli temsil biçimi AIvalueAIvalue şeklindedir. Bir değerin içinde bulunan gerçek açılı parantez '(' olarak yazılmalıdır; bu tek desteklenen kaçış dizisidir. Bir değerin içinde bulunan kapanış parantez ')' kaçış gerektirmez."
type: docs
weight: 530
url: /tr/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

GS1 kod metnini, Uygulama Tanımlayıcı (Application Identifier) öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Köşeli gösterim (AI)değer(AI)değer biçimindedir. Bir değerin içinde gerçek bir açılış parantezi '(' \( olarak yazılmalıdır; bu tek desteklenen kaçış dizisidir. Bir değerin içinde kapanış parantezi ')' kaçış gerektirmez.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Bu GS1 codetext'i kodlamak için kullanılan barkod tipini alır veya ayarlar. Desteklenen tipler GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR ve GS1 DataBar tipleridir. Varsayılan değer GS1Code128'dir. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Application Identifier öğelerinin sayısını alır. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Tüm öğelerin kaynak sırasındaki bir kopyasını alır. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Sıralı dizideki konumuna göre bir öğeyi alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Bir (AI)değer(AI)değer biçimindeki köşeli GS1 öğe dizesini ayrıştırır. Bir değerin içinde gerçek '(' karakteri \\( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Doğrulanmış bir Application Identifier öğesini ekler. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Bir Application Identifier için tüm değerleri kaynak sırasına göre alır. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Bu GS1 codetext'i kodlamak için kullanılan barkod tipini alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Parantezli GS1 kod metnini (AI)değer(AI)değer biçiminde oluşturur. Değerlerdeki gerçek açma parantezleri \\( olarak kaçış yapılır. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Bir Application Identifier için ilk değeri alır. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Bu örneği, (AI)değer(AI)değer biçimindeki parantezli GS1 kod metninden başlatır. Mevcut öğeler, sağlanan kod metni başarıyla ayrıştırıldıktan sonra yalnızca değiştirilir. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Parantezli GS1 temsili (AI)değer(AI)değer biçiminde döndürür. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Parantezli GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırmayı dener ve yapılandırılmış doğrulama hataları döndürür. Bir değerdeki gerçek '(' karakteri \\( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Parantezli GS1 öğe dizesini (AI)değer(AI)değer biçiminde nesne oluşturmadan doğrular. Bir değerdeki gerçek '(' karakteri \\( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


