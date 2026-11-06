---
title: "Aspose::BarCode::Generation::BaseGenerationParameters class"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters class. معلمات توليد صورة الباركود في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


معلمات توليد صورة الباركود.

```cpp
class BaseGenerationParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | لون الخلفية لصورة الباركود. القيمة الافتراضية: Color.White. انظر [Color](../). |
| [get_Barcode](./get_barcode/)() const | يحصل على [BarcodeParameters](../barcodeparameters/) التي تحتوي على جميع خصائص الباركود. |
| [get_Border](./get_border/)() const | يحصل على [BorderParameters](../borderparameters/) التي تحتوي على جميع خصائص التكوين لإطار الباركود. |
| [get_CaptionAbove](./get_captionabove/)() const | التسمية التوضيحية فوق صورة [BarCode](../../aspose.barcode/). راجع [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | التسمية التوضيحية أسفل صورة [BarCode](../../aspose.barcode/). راجع [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | معلمات الصورة. راجع [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | ارتفاع صورة [BarCode](../../aspose.barcode/) عندما تكون خاصية [AutoSizeMode](../autosizemode/) مضبوطة على [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | عرض صورة [BarCode](../../aspose.barcode/) عندما تكون خاصية [AutoSizeMode](../autosizemode/) مضبوطة على [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | يحصل على دقة صورة [BarCode](../../aspose.barcode/). قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 نقطة في البوصة. |
| [get_RotationAngle](./get_rotationangle/)() const | زاوية دوران صورة [BarCode](../../aspose.barcode/)، مقاسة بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الماسح للصورة. القيمة الافتراضية: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | يحصل على قيمة تشير إلى ما إذا كان وضع مكافحة التعرجات مستخدمًا لتصيير الصورة |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | لون الخلفية لصورة الباركود. القيمة الافتراضية: Color.White. انظر [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | ارتفاع صورة [BarCode](../../aspose.barcode/) عندما تكون خاصية [AutoSizeMode](../autosizemode/) مضبوطة على [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | عرض صورة [BarCode](../../aspose.barcode/) عندما تكون خاصية [AutoSizeMode](../autosizemode/) مضبوطة على [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | يضبط دقة صورة [BarCode](../../aspose.barcode/). قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 نقطة في البوصة. |
| [set_RotationAngle](./set_rotationangle/)(float) | زاوية دوران صورة [BarCode](../../aspose.barcode/)، مقاسة بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الماسح للصورة. القيمة الافتراضية: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | يضبط قيمة تشير إلى ما إذا كان وضع مكافحة التعرجات مستخدمًا لتصيير الصورة |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
