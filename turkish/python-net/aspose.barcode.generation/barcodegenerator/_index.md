---
title: "BarcodeGenerator"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

Arka uç barkod görüntüsü oluşturma için BarcodeGenerator.

BarcodeGenerator türü aşağıdaki üyeleri sunar:
## Constructors
| Ad | Açıklama |
| :- | :- |
| BarcodeGenerator(type) | BarcodeGenerator sınıfının yeni bir örneğini başlatır |
| BarcodeGenerator(type, code_text) | BarcodeGenerator sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| parametreler | Oluşturma parametreleri. |
| barcode_type | Barkod semboloji türü. |
| code_text | Kodlanacak metin. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| set_code_text(code_bytes) | Kod metnini bayt dizisi olarak ayarlar. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Barkod görüntüsünü belirli formatta akışa kaydeder. |
| save(filename, format) | Barkod görüntüsünü belirli bir dosyaya belirli formatta kaydeder. |
| save(filename) | Barkod görüntüsünü belirli bir dosyaya belirli formatta kaydeder. |
| export_to_xml(xml_file) | Belirtilen xml dosyasına BarCode özelliklerini dışa aktarır |
| export_to_xml(xml) | Belirtilen xml akışına BarCode özelliklerini dışa aktarır |
| import_from_xml(xml_file) | Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| import_from_xml(xml) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| generate_bar_code_image() | Mevcut ayarlar altında barkod görüntüsünü oluşturur. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

