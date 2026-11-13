---
title: "GS1Codetext"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

GS1 kod metnini kodlamak ve çözmek için sıralı bir <br/> Application Identifier öğeleri dizisi olarak temsil eder. Kaynak sırası ve tekrarlanan Application Identifier'lar korunur. Köşeli gösterim (AI)değer(AI)değer biçimindedir. Bir değerin içinde bulunan gerçek bir açma parantez '(' \; olarak yazılmalıdır; bu tek desteklenen kaçış dizisidir. Bir kapanma parantez ')' değerin içinde kaçış gerektirmez.

GS1Codetext türü aşağıdaki üyeleri gösterir:
## Constructors
| Ad | Açıklama |
| :- | :- |
| GS1Codetext() | GS1Codetext sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| barcode_type | Bu GS1 kod metnini kodlamak için kullanılan barkod tipini alır veya ayarlar.<br/>            Desteklenen tipler GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR ve GS1 DataBar tipleridir.<br/>            Varsayılan değer GS1Code128'dir. |
| sayım | Uygulama Tanımlayıcı öğelerinin sayısını alır. |
| öğeler | Kaynak sırasındaki tüm öğelerin bir kopyasını alır. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Sıralı dizideki konumuna göre bir öğeyi alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| get_first(application_identifier) | Bir Uygulama Tanımlayıcısı için ilk değeri alır. |
| get_all(application_identifier) | Bir Uygulama Tanımlayıcısı için tüm değerleri kaynak sırasıyla alır. |
| add(application_identifier, value) | Doğrulanmış bir Uygulama Tanımlayıcısı öğesini ekler. |
| validate(value) | Bir (AI)değer(AI)değer biçimindeki parantezli GS1 öğe dizesini nesne oluşturmadan doğrular.<br/>            Bir değerdeki gerçek '(' karakteri \( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| parse(value) | Bir (AI)değer(AI)değer biçimindeki parantezli GS1 öğe dizesini ayrıştırır. Bir değerdeki gerçek<br/>            '(' karakteri \( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez,<br/>            ve ')' kaçış gerektirmez. |
| try_parse(value, result, validation_result) | Bir (AI)değer(AI)değer biçimindeki parantezli GS1 öğe dizesini ayrıştırmayı dener<br/>            ve yapılandırılmış doğrulama hatalarını döndürür. Bir değerdeki gerçek '(' karakteri<br/>            \( olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez. |
| get_constructed_codetext() | Parantezli GS1 kod metnini (AI)değer(AI)değer biçiminde oluşturur.<br/>            Değerlerdeki gerçek açılış parantezleri \( olarak kaçış yapılır. |
| init_from_string(constructed_codetext) | Bu örneği (AI)değer(AI)değer biçimindeki parantezli GS1 kod metninden başlatır.<br/>            Mevcut öğeler, sağlanan kod metni başarıyla ayrıştırıldıktan sonra yalnızca değiştirilir. |
| get_barcode_type() | Bu GS1 kod metnini kodlamak için kullanılan barkod tipini alır. |

### Ayrıca Bakınız

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

