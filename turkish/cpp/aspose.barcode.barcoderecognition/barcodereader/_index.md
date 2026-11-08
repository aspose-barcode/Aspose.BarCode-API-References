---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader class"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader sınıfı. BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsüller, ardından C++'ta barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Abort](./abort/)() | Fonksiyon, mevcut tanıma oturumunun diğer bir iş parçacığından sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. Tanıma süreci çok uzun olduğunda bu yöntem kullanılmalıdır. |
| [BarCodeReader](./barcodereader/)() | Varsayılan değerlerle yeni bir [BarCodeReader](./) sınıfı örneği başlatır. [ReadBarCodes()](./readbarcodes/) yöntemini çağırmadan önce görüntünün (SetBitmapImage()) ayarlanması gerekir. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Bir görüntüden yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::String) | Dosyadan yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Bir parlaklık çerçevesinden yeni bir [BarCodeReader](./) sınıfı örneği başlatır. |
| [Dispose](./dispose/)() override | Kaynağı serbest bırak |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) özelliklerini belirtilen xml dosyasına dışa aktarır |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) özelliklerini belirtilen xml akışına dışa aktarır |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Tanıma için kullanılan barkod çözümleme tipini alır. [ReadBarCodes](./readbarcodes/) çağrılmadan önce ayarlanmalıdır. |
| [get_BarcodeSettings](./get_barcodesettings/)() | Ana [BarCode](../../aspose.barcode/) çözümleme parametreleri. Tanınan veriler üzerinde etkisi olan parametreleri içerir. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Tanınan [BarCodeResult](../barcoderesult/) dizisini alır |
| [get_FoundCount](./get_foundcount/)() | Tanınan barkod sayısını alır |
| static [get_ProcessorSettings](./get_processorsettings/)() | İşlemci çekirdeklerinin kullanım ayarını alır. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. Gömülü ön ayarlar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes kullanarak [QualitySettings](../qualitysettings/) hızlı bir şekilde ayarlayabilirsiniz veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. [QualitySettings](../qualitysettings/) varsayılan değeri NormalQuality'dir. |
| [get_Timeout](./get_timeout/)() | Tanıma işleminin zaman aşımını milisaniye cinsinden alır. |
| static [ImportFromXml](./importfromxml/)(System::String) | Belirtilen xml dosyasından [BarCode](../../aspose.barcode/) özelliklerini içe aktarır ve mevcut [BarCodeReader](./) örneğine uygular. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Belirtilen xml akışından [BarCode](../../aspose.barcode/) özelliklerini içe aktarır ve mevcut [BarCodeReader](./) örneğine uygular. |
| [ReadBarCodes](./readbarcodes/)() | Görüntüden [BarCodeResult](../barcoderesult/) sonuçlarını okur. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Tanıma için kullanılan barkod çözümleme tipini ayarlar. [ReadBarCodes](./readbarcodes/) çağrılmadan önce ayarlanmalıdır. |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. Gömülü ön ayarlar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes kullanarak [QualitySettings](../qualitysettings/) hızlı bir şekilde ayarlayabilirsiniz veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. [QualitySettings](../qualitysettings/) varsayılan değeri NormalQuality'dir. |
| [set_Timeout](./set_timeout/)(int32_t) | Tanıma işleminin zaman aşımını milisaniye cinsinden ayarlar. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Tanıma için bitmap görüntüsünü ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Tanıma için bitmap görüntüsü ve alanlarını ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Tanıma için bitmap görüntüsü ve alanı ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Tanıma için görüntü dosyasını ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Tanıma için görüntü akışını ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Tanıma için parlaklık çerçevesi ve alanını ayarlar. [ReadBarCodes](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Tanıma için parlaklık çerçevesi ve alanlarını ayarlar. [ReadBarCodes](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Tanıma için parlaklık çerçevesini ayarlar. [ReadBarCodes](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [SingleDecodeType](../singledecodetype/) tip dizisini tanıma için ayarlar. [ReadBarCodes()](./readbarcodes/) yönteminden önce çağrılmalıdır. |
## Açıklamalar


Bu örnek, Code39 ve Code128 barkodlarının nasıl tespit edileceğini gösterir.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
