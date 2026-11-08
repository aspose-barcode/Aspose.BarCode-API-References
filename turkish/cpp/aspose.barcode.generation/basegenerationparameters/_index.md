---
title: "Aspose::BarCode::Generation::BaseGenerationParameters sınıfı"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::BaseGenerationParameters sınıfı. C++'da barkod görüntüsü oluşturma parametreleri."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Barkod görüntüsü oluşturma parametreleri.

```cpp
class BaseGenerationParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Otomatik boyutlandırma modlarının farklı türlerini belirtir. Varsayılan değer: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Barkod görüntüsünün arka plan rengi. Varsayılan değer: Color.White. Bakınız [Color](../). |
| [get_Barcode](./get_barcode/)() const | [BarcodeParameters](../barcodeparameters/) içindeki tüm barkod özelliklerini alır. |
| [get_Border](./get_border/)() const | [BorderParameters](../borderparameters/) içindeki barkod kenarı için tüm yapılandırma özelliklerini alır. |
| [get_CaptionAbove](./get_captionabove/)() const | Resmin üzerindeki altyazı. [BarCode](../../aspose.barcode/) resmi. Daha fazla bilgi için [CaptionParameters](../captionparameters/) sayfasına bakın. |
| [get_CaptionBelow](./get_captionbelow/)() const | Resmin altındaki altyazı. [BarCode](../../aspose.barcode/) resmi. Daha fazla bilgi için [CaptionParameters](../captionparameters/) sayfasına bakın. |
| [get_Image](./get_image/)() const | Görüntü parametreleri. Daha fazla bilgi için [ImageParameters](../imageparameters/) sayfasına bakın. |
| [get_ImageHeight](./get_imageheight/)() const | [BarCode](../../aspose.barcode/) resmi yüksekliği, [AutoSizeMode](../autosizemode/) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlandığında. |
| [get_ImageWidth](./get_imagewidth/)() const | [BarCode](../../aspose.barcode/) resmi genişliği, [AutoSizeMode](../autosizemode/) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlandığında. |
| [get_Resolution](./get_resolution/)() const | [BarCode](../../aspose.barcode/) resminin çözünürlüğünü alır. Her iki boyut için aynı değer. Varsayılan değer: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | [BarCode](../../aspose.barcode/) resmi döndürme açısı, derece cinsinden ölçülür, ör. RotationAngle = 0 veya RotationAngle = 360 döndürme olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının resmi okumasını zorlaştırabilir. Varsayılan değer: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Görüntüyü renderlamak için anti-aliasing modunun kullanılıp kullanılmadığını belirten bir değer alır. |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Otomatik boyutlandırma modlarının farklı türlerini belirtir. Varsayılan değer: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Barkod görüntüsünün arka plan rengi. Varsayılan değer: Color.White. Bakınız [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) resmi yüksekliği, [AutoSizeMode](../autosizemode/) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlandığında. |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | [BarCode](../../aspose.barcode/) resmi genişliği, [AutoSizeMode](../autosizemode/) özelliği [AutoSizeMode.Nearest](../autosizemode/) veya [AutoSizeMode.Interpolation](../autosizemode/) olarak ayarlandığında. |
| [set_Resolution](./set_resolution/)(float) | [BarCode](../../aspose.barcode/) resminin çözünürlüğünü ayarlar. Her iki boyut için aynı değer. Varsayılan değer: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | [BarCode](../../aspose.barcode/) resmi döndürme açısı, derece cinsinden ölçülür, ör. RotationAngle = 0 veya RotationAngle = 360 döndürme olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının resmi okumasını zorlaştırabilir. Varsayılan değer: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Görüntüyü renderlamak için anti-aliasing modunun kullanılıp kullanılmadığını belirten bir değer ayarlar. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
