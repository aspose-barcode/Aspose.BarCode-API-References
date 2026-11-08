---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink sınıfı. GS1 Digital Link kod metnini, Uygulama Tanımlayıcı öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Oluşturulan kod metni sıkıştırılmamış bir GS1 Digital Link URI'sıdır. GS1 dışı sorgu parametreleri ve URI parçacıkları C++'ta ayrıştırma sırasında yok sayılır."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


GS1 Digital Link kod metnini, Uygulama Tanımlayıcı öğelerinin sıralı bir dizisi olarak kodlamak ve çözmek için temsil eder. Kaynak sırası ve tekrarlanan Uygulama Tanımlayıcıları korunur. Oluşturulan kod metni sıkıştırılmamış bir GS1 Digital Link URI'sidir. Ayrıştırma sırasında GS1 dışı sorgu parametreleri ve URI parçacıkları yok sayılır.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Doğrulanmış bir Uygulama Tanımlayıcı öğesi ekler. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | GS1 kod metnindeki tüm öğeleri kopyalayarak ve mevcut tek birincil anahtarı seçerek bir GS1 Digital Link oluşturur. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | GS1 kod metnindeki tüm öğeleri kopyalayarak ve belirtilen birincil anahtarı kullanarak bir GS1 Digital Link oluşturur. |
| [get_BarcodeType](./get_barcodetype/)() const | Bu GS1 Digital Link'i kodlamak için kullanılan barkod tipini alır. Desteklenen tipler QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF ve Code128'dir. Varsayılan değer QR'dir. |
| [get_Count](./get_count/)() | Uygulama Tanımlayıcı öğelerinin sayısını alır. |
| [get_Elements](./get_elements/)() | Kaynak sırasındaki tüm öğelerin bir kopyasını alır. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Digital Link birincil anahtarı olarak kullanılan Uygulama Tanımlayıcıyı alır. Null, URI oluşturulduğunda birincil anahtarın otomatik olarak seçileceği anlamına gelir. |
| [get_UriStem](./get_uristem/)() const | GS1 birincil anahtar yol segmentinden önceki mutlak URI önekini alır. Kök, bir sorgu dizesi veya parça içermez. |
| [GetAll](./getall/)(System::String) | Bir Uygulama Tanımlayıcısı için tüm değerleri kaynak sırasıyla alır. |
| [GetBarcodeType](./getbarcodetype/)() override | Bu GS1 Dijital Bağlantıyı kodlamak için kullanılan barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Sıkıştırılmamış GS1 Dijital Bağlantı URI'sını oluşturur. |
| [GetFirst](./getfirst/)(System::String) | Bir Uygulama Tanımlayıcısı için ilk değeri alır. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Belirtilen URI köküyle boş bir GS1 Dijital Bağlantı başlatır. Birincil anahtar, tam olarak bir birincil‑anahtar adayı mevcut olduğunda otomatik olarak seçilir. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Belirtilen URI kökü ve birincil anahtar ile boş bir GS1 Dijital Bağlantı başlatır. |
| [idx_get](./idx_get/)(int32_t) | Sıralı dizideki konumuna göre bir öğeyi alır. |
| [InitFromString](./initfromstring/)(System::String) override | Bu örneği sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sinden başlatır. Mevcut durum, sağlanan URI başarıyla ayrıştırıldıktan sonra yalnızca değiştirilir. Seçilen barkod tipi korunur. |
| static [Parse](./parse/)(System::String) | Sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sini ayrıştırır. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Bu GS1 Dijital Bağlantıyı kodlamak için kullanılan barkod tipini ayarlar. Desteklenen tipler QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF ve Code128'dir. Varsayılan değer QR'dir. |
| [ToGS1Codetext](./togs1codetext/)() | Mevcut GS1 öğelerini içeren bağımsız bir GS1 kod metni oluşturur. Yalnızca URI bilgisi dahil edilmez. |
| [ToString](./tostring/)() const override | Sıkıştırılmamış GS1 Dijital Bağlantı URI'sını döndürür. |
| [ToUriString](./touristring/)() | Mevcut nesne durumunu sıkıştırılmamış bir GS1 Dijital Bağlantı URI'si olarak biçimlendirir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sini ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür. |
| static [Validate](./validate/)(System::String) | Bir nesne oluşturmadan sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sini doğrular. |
## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
