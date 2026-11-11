---
title: "Class GS1DigitalLink"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink sınıfı. Uygulama Tanımlayıcı öğelerinin sıralı bir dizisi olarak kodlama ve kod çözme için GS1 Digital Link kod metnini temsil eder. Kaynak sıra ve tekrarlanan Uygulama Tanımlayıcıları korunur. Oluşturulan kod metni sıkıştırılmamış bir GS1 Digital Link URI'sidir. Ayrıştırma sırasında NonGS1 sorgu parametreleri ve URI parçacıkları göz ardı edilir."
type: docs
weight: 540
url: /tr/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

GS1 Digital Link kod metnini, Uygulama Tanımlayıcı (Application Identifier) öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Oluşturulan kod metni sıkıştırılmamış bir GS1 Digital Link URI'sidir. Ayrıştırma sırasında GS1 olmayan sorgu parametreleri ve URI parçacıkları yok sayılır.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Belirtilen URI köküyle boş bir GS1 Digital Link başlatır. Tam olarak bir birincil anahtar adayı mevcut olduğunda birincil anahtar otomatik olarak seçilir. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Belirtilen URI kökü ve birincil anahtar ile boş bir GS1 Digital Link başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Bu GS1 Digital Link'i kodlamak için kullanılan barkod tipini alır veya ayarlar. Desteklenen tipler QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF ve Code128'dir. Varsayılan değer QR'dir. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Application Identifier öğelerinin sayısını alır. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Tüm öğelerin kaynak sırasındaki bir kopyasını alır. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Sıralı dizideki konumuna göre bir öğeyi alır. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Digital Link birincil anahtarı olarak kullanılan Application Identifier'ı alır. Null, URI oluşturulduğunda birincil anahtarın otomatik olarak seçildiği anlamına gelir. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | GS1 birincil anahtar yol segmentinden önceki mutlak URI önekini alır. Kök, sorgu dizesi veya parça içermez. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | GS1 codetext'ten tüm öğeleri kopyalayarak ve tek mevcut birincil anahtarı seçerek bir GS1 Digital Link oluşturur. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | GS1 codetext'ten tüm öğeleri kopyalayarak ve belirtilen birincil anahtarı kullanarak bir GS1 Digital Link oluşturur. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Sıkıştırılmamış bir GS1 Digital Link URI'sini ayrıştırır. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Doğrulanmış bir Application Identifier öğesini ekler. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Bir Application Identifier için tüm değerleri kaynak sırasına göre alır. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Bu GS1 Digital Link'i kodlamak için kullanılan barkod tipini alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Sıkıştırılmamış GS1 Digital Link URI'sini oluşturur. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Bir Application Identifier için ilk değeri alır. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Bu örneği sıkıştırılmamış bir GS1 Digital Link URI'sinden başlatır. Mevcut durum, sağlanan URI başarıyla ayrıştırıldıktan sonra yalnızca değiştirilir. Seçilen barkod tipi korunur. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Mevcut GS1 öğelerini içeren bağımsız bir GS1 codetext oluşturur. Yalnızca URI bilgisi dahil edilmez. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Sıkıştırılmamış GS1 Digital Link URI'sini döndürür. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Mevcut nesne durumunu sıkıştırılmamış bir GS1 Digital Link URI'si olarak biçimlendirir. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Sıkıştırılmamış bir GS1 Digital Link URI'sini ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Bir nesne oluşturmadan sıkıştırılmamış bir GS1 Digital Link URI'sini doğrular. |

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


