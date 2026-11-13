---
title: "QualitySettings"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا.<br/>            يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxQuality أو يمكنك تكوين الخيارات المنفصلة يدويًا.<br/>            القيمة الافتراضية لـ QualitySettings هي NormalQuality.

يعرض نوع QualitySettings الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| high_performance | إعداد مسبق لجودة التعرف عالية الأداء. يتم التعرف على الباركودات ذات الجودة العالية بشكل جيد في هذا الوضع. |
| normal_quality | إعداد جودة التعرف NormalQuality. مناسب لمعظم الباركودات |
| high_quality | إعداد جودة التعرف HighQuality. تم تطوير هذا الإعداد للباركودات منخفضة الجودة. يسمح باكتشاف الباركودات المتضررة بشدة. |
| max_quality | إعداد جودة التعرف MaxQuality. تم تطوير هذا الإعداد للتعرف على جميع الباركودات الممكنة، حتى الباركودات غير الصحيحة. |
| x_dimension | وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية المصفوفة أو الشريط. |
| minimal_x_dimension | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| barcode_quality | وضع يتيح الطرق للتعرف على عناصر الباركود بالجودة المختارة. العنصر ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف. |
| deconvolution | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة <br/>            (convoluted) بأي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. لأنه لا يمكننا اكتشاف الدالة التي تفسد الصورة، <br/>            علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي. |
| inverse_image | وضع يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة). |
| complex_background | وضع يتيح أو يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| allow_incorrect_barcodes | يسمح للمحرك بالتعرف على الباركودات التي تحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات المتضررة ذات النص غير الصحيح. |

### انظر أيضًا

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

