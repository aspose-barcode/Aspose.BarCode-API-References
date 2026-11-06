---
title: "فئة Aspose::BarCode::BarCodeRecognition::QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::QualitySettings. يتيح QualitySettings تكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxQuality أو يمكنك تكوين الخيارات بشكل منفصل يدويًا. القيمة الافتراضية لـ QualitySettings هي NormalQuality في C++."
type: docs
weight: 3100
url: /ar/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | يسمح للمحرك بالتعرف على الباركودات التي لديها مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح. |
| [get_BarcodeQuality](./get_barcodequality/)() const | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف. |
| [get_ComplexBackground](./get_complexbackground/)() const | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| [get_Deconvolution](./get_deconvolution/)() const | وضع فك الالتفاف (استعادة الصورة) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. نظرًا لعدم قدرتنا على اكتشاف الدالة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي. |
| static [get_HighPerformance](./get_highperformance/)() | إعداد مسبق لجودة التعرف HighPerformance. يتم التعرف على الباركودات عالية الجودة بشكل جيد في هذا الوضع. |
| static [get_HighQuality](./get_highquality/)() | إعداد مسبق لجودة التعرف HighQuality. تم تطوير هذا الإعداد للباركودات منخفضة الجودة. يسمح باكتشاف الباركودات المتضررة بشدة. |
| [get_InverseImage](./get_inverseimage/)() const | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (السطوع). |
| static [get_MaxQuality](./get_maxquality/)() | إعداد مسبق لجودة التعرف MaxQuality. تم تطوير هذا الإعداد المسبق للتعرف على جميع الباركود الممكنة، حتى الباركود غير الصحيحة. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | إعداد مسبق لجودة التعرف NormalQuality. مناسب لمعظم الباركود. |
| [get_XDimension](./get_xdimension/)() const | وضع [Recognition](../../aspose.barcode.barcoderecognition.recognition/) الذي يحدد الحجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية المصفوفة أو الشريط. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | يسمح للمحرك بالتعرف على الباركودات التي لديها مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | وضع فك الالتفاف (استعادة الصورة) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. نظرًا لعدم قدرتنا على اكتشاف الدالة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (السطوع). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | وضع [Recognition](../../aspose.barcode.barcoderecognition.recognition/) الذي يحدد الحجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية المصفوفة أو الشريط. |
## ملاحظات


هذا المثال يوضح كيفية استخدام [QualitySettings](./) مع [BarCodeReader](../barcodereader/)
```cpp
[C#]
//تعيين وضع HighPerformance للتعرف
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//تعيين وضع HighQuality للتعرف
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//تعيين وضع HighPerformance للتعرف للباركود ذات الحجم الصغير
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//تعيين وضع HighPerformance للتعرف للباركود ذات الجودة المنخفضة
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
