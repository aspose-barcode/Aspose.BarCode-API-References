---
title: "GS1DigitalLink"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

GS1 Digital Link kod metnini kodlamak ve çözmek için sıralı bir <br/> Application Identifier öğeleri dizisi olarak temsil eder. Kaynak sırası ve tekrarlanan Application Identifier'lar korunur. Oluşturulan kod metni sıkıştırılmamış bir GS1 Digital Link URI'sidir. Ayrıştırma sırasında GS1 dışı sorgu parametreleri ve URI parçacıkları yok sayılır.

GS1DigitalLink türü aşağıdaki üyeleri sunar:
## Constructors
| Ad | Açıklama |
| :- | :- |
| GS1DigitalLink(uri_stem) | GS1DigitalLink sınıfının yeni bir örneğini başlatır |
| GS1DigitalLink(uri_stem, primary_application_identifier) | GS1DigitalLink sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| uri_stem | GS1 birincil anahtar yol segmentinden önceki mutlak URI önekini alır.<br/>            Stem, bir sorgu dizesi veya fragment içermez. |
| primary_application_identifier | Digital Link birincil anahtarı olarak kullanılan Uygulama Tanımlayıcısını alır.<br/>            Null, URI oluşturulduğunda birincil anahtarın otomatik olarak seçildiği anlamına gelir. |
| barcode_type | Bu GS1 Digital Link'i kodlamak için kullanılan barkod tipini alır veya ayarlar.<br/>            Desteklenen tipler QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF ve Code128'dir.<br/>            Varsayılan değer QR'dir. |
| sayım | Uygulama Tanımlayıcı öğelerinin sayısını alır. |
| öğeler | Kaynak sırasındaki tüm öğelerin bir kopyasını alır. |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Sıralı dizideki konumuna göre bir öğeyi alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| create(uri_stem, codetext) | GS1 kod metninden tüm öğeleri kopyalayarak ve tek mevcut birincil anahtarı seçerek bir GS1 Dijital Bağlantı oluşturur<br/>            . |
| create(uri_stem, codetext, primary_application_identifier) | GS1 kod metninden tüm öğeleri kopyalayarak ve tek mevcut birincil anahtarı seçerek bir GS1 Dijital Bağlantı oluşturur<br/>            . |
| get_first(application_identifier) | Bir Uygulama Tanımlayıcısı için ilk değeri alır. |
| get_all(application_identifier) | Bir Uygulama Tanımlayıcısı için tüm değerleri kaynak sırasıyla alır. |
| add(application_identifier, value) | Doğrulanmış bir Uygulama Tanımlayıcısı öğesini ekler. |
| validate(value) | Bir nesne oluşturmadan sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sını doğrular. |
| parse(value) | Sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sını ayrıştırır. |
| try_parse(value, result, validation_result) | Sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sını ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür. |
| to_gs1_codetext() | Mevcut GS1 öğelerini içeren bağımsız bir GS1 kod metni oluşturur.<br/>            Yalnızca URI bilgisi dahil edilmez. |
| to_uri_string() | Mevcut nesne durumunu sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sı olarak biçimlendirir. |
| get_constructed_codetext() | Sıkıştırılmamış GS1 Dijital Bağlantı URI'sını oluşturur. |
| init_from_string(constructed_codetext) | Bu örneği sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sından başlatır.<br/>            Sağlanan URI başarıyla ayrıştırıldıktan sonra mevcut durum yalnızca o zaman değiştirilir.<br/>            Seçilen barkod türü korunur. |
| get_barcode_type() | Bu GS1 Dijital Bağlantıyı kodlamak için kullanılan barkod türünü alır. |

### Ayrıca Bakınız

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

