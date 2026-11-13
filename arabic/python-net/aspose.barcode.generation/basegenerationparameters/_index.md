---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

معلمات توليد صورة الباركود.

يعرض نوع BaseGenerationParameters الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| use_anti_alias | يحصل أو يعيّن قيمة تشير إلى ما إذا كان وضع مكافحة التعرج مُستخدمًا لتصوير الصورة |
| back_color | لون الخلفية لصورة الباركود.<br/>            القيمة الافتراضية: Color.White.<br/>            انظر [Color](/barcode/python-net/aspose.drawing/color/). |
| دقة | يحصل أو يعيّن دقة صورة الباركود.<br/>            قيمة واحدة لكلا البعدين.<br/>            القيمة الافتراضية: 96 dpi. |
| rotation_angle | زاوية دوران صورة الباركود، مقاسة بالدرجة، مثال: RotationAngle = 0 أو RotationAngle = 360 يعني لا دوران.<br/>            إذا لم تكن RotationAngle مساوية لـ 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الماسح للصورة.<br/>            القيمة الافتراضية: 0. |
| caption_above | التسمية التوضيحية فوق صورة الباركود. انظر [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | التسمية التوضيحية أسفل صورة الباركود. انظر [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | معلمات الصورة. انظر [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي.<br/>            القيمة الافتراضية: AutoSizeMode.None. |
| image_height | ارتفاع صورة BarCode عندما يتم تعيين خاصية [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| image_width | عرض صورة BarCode عندما يتم تعيين خاصية [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| barcode | يحصل على [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) التي تحتوي على جميع خصائص الباركود. |
| border | يحصل على [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) التي تحتوي على جميع خصائص التكوين لإطار الباركود. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

