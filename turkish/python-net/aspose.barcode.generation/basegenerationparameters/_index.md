---
title: "BaseGenerationParameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Barkod görüntüsü oluşturma parametreleri.

BaseGenerationParameters türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| use_anti_alias | Görüntüyü işlemek için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar |
| back_color | Barkod görüntüsünün arka plan rengi.<br/>            Varsayılan değer: Color.White.<br/>            Bakınız [Color](/barcode/python-net/aspose.drawing/color/). |
| çözünürlük | BarCode görüntüsünün çözünürlüğünü alır veya ayarlar.<br/>            Her iki boyut için aynı değer.<br/>            Varsayılan değer: 96 dpi. |
| rotation_angle | BarCode görüntüsü dönüş açısı, derece cinsinden ölçülür, örn. RotationAngle = 0 veya RotationAngle = 360 dönüş olmadığını gösterir.<br/>            RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir.<br/>            Varsayılan değer: 0. |
| caption_above | BarCode görüntüsünün üzerindeki başlık. Bakınız [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | BarCode görüntüsünün altındaki başlık. Bakınız [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Görüntü parametreleri. Bakınız [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Otomatik boyutlandırma modlarının farklı türlerini belirtir.<br/>            Varsayılan değer: AutoSizeMode.None. |
| image_height | BarCode görüntü yüksekliği, [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| image_width | BarCode görüntü genişliği, [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| barcode | Alır [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) nesnesini; bu nesne tüm barkod özelliklerini içerir. |
| border | Alır [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) nesnesini; bu nesne barkod kenarı için tüm yapılandırma özelliklerini içerir. |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

