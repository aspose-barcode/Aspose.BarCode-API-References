---
title: "BarCodeReader"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsüller, ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir.

BarCodeReader türü aşağıdaki üyeleri ortaya çıkarır:
## Constructors
| Ad | Açıklama |
| :- | :- |
| BarCodeReader() | Varsayılan değerlerle yeni bir [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) sınıfı örneği başlatır.<br/>            ReadBarCodes() metodunu çağırmadan önce görüntünün (SetBitmapImage()) ayarlanması gerekir. |
| BarCodeReader(image) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, area, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, area, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, areas, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(image, areas, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(filename) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(filename, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(filename, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(stream) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(stream, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(stream, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, areas, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, areas, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, area, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, area, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, type) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame, decode_types) | BarCodeReader sınıfının yeni bir örneğini başlatır |
| BarCodeReader(frame) | BarCodeReader sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| processor_settings | İşlemci çekirdeklerini kullanma ayarlarını alır. |
| timeout | Tanıma işleminin zaman aşımını milisaniye cinsinden alır veya ayarlar. |
| found_bar_codes | Tanımlanan [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) dizisini alır |
| found_count | Tanımlanan barkod sayısını alır |
| quality_settings | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza izin verir.<br/>            QualitySettings'i gömülü ön ayarlar: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes ile hızlı bir şekilde ayarlayabilirsiniz veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz.<br/>            QualitySettings'in varsayılan değeri NormalQuality'dir. |
| barcode_settings | Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreleri içerir. |
| bar_code_read_type | Tanıma için kullanılan barkod çözümleme türünü alır veya ayarlar.<br/>            [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) çağrılmadan önce ayarlanmalıdır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| set_bar_code_image(value) | Tanıma için bitmap görüntüsünü ayarlar. <br/>            ReadBarCodes() yönteminden önce çağrılmalıdır. |
| set_bar_code_image(value, areas) | Tanıma için bitmap görüntüsünü ve alanları ayarlar. <br/>            ReadBarCodes() yönteminden önce çağrılmalıdır. |
| set_bar_code_image(value, area) | Tanıma için bitmap görüntüsünü ve alanları ayarlar. <br/>            ReadBarCodes() yönteminden önce çağrılmalıdır. |
| set_bar_code_image(filename) | Tanıma için görüntü dosyasını ayarlar. <br/>            ReadBarCodes() yönteminden önce çağrılmalıdır. |
| set_bar_code_image(stream) | Tanıma için görüntü akışını ayarlar. <br/>            ReadBarCodes() yönteminden önce çağrılmalıdır. |
| set_bar_code_image(frame, area) | Tanıma için parlaklık çerçevesini ve alanı ayarlar. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) yönteminden önce çağrılmalıdır. |
| set_bar_code_image(frame, areas) | Tanıma için parlaklık çerçevesini ve alanları ayarlar. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) yönteminden önce çağrılmalıdır. |
| set_bar_code_image(frame) | Tanıma için parlaklık çerçevesini ve alanı ayarlar. [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) yönteminden önce çağrılmalıdır. |
| export_to_xml(xml_file) | Belirtilen xml dosyasına BarCode özelliklerini dışa aktarır |
| export_to_xml(xml_stream) | Belirtilen xml akışına BarCode özelliklerini dışa aktarır |
| import_from_xml(xml_file) | Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| import_from_xml(xml_stream) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| abort() | Fonksiyon, başka bir iş parçacığından mevcut tanıma oturumunun sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. <br/>            Tanıma işlemi çok uzun sürdüğünde bu yöntem kullanılmalıdır. |
| read_bar_codes() | Görüntüden [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) nesnelerini okur. |
| set_bar_code_read_type(barcode_types) | Tanıma için [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) tip dizisini ayarlar. <br/> ReadBarCodes() metodundan önce çağrılmalıdır. |

### Ayrıca Bakınız

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

