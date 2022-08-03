---
title: QualitySettings
second_title: Aspose.BarCode لمرجع .NET API
description: QualitySettings تسمح بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد QualitySettings بسرعة من خلال الإعدادات المسبقة المضمنة HighPerformance  NormalQuality  HighQuality  MaxBarCodes أو يمكنك تكوين خيارات منفصلة يدويًا . القيمة الافتراضية لإعدادات الجودة هي NormalQuality .
type: docs
weight: 250
url: /ar/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings تسمح بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد QualitySettings بسرعة من خلال الإعدادات المسبقة المضمنة: HighPerformance ، NormalQuality ، HighQuality ، MaxBarCodes أو يمكنك تكوين خيارات منفصلة يدويًا . القيمة الافتراضية لإعدادات الجودة هي NormalQuality .

```csharp
public sealed class QualitySettings
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | ضبط مسبق لجودة التعرف على الأداء العالي. يتم التعرف على الرموز الشريطية عالية الجودة بشكل جيد في هذا الوضع. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | ضبط مسبق لجودة التعرف على الجودة العالية. تم تطوير هذا الإعداد المسبق للرموز الشريطية منخفضة الجودة. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | ضبط مسبق لجودة التعرف على HighQualityDetection. نفس الجودة العادية ولكن بجودة عالية[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | ضبط جودة التعرف على MaxBarCodes مسبقًا. تم تطوير هذا الإعداد المسبق للتعرف على جميع الرموز الشريطية الممكنة ، حتى الرموز الشريطية غير الصحيحة. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | ضبط مسبق لجودة التعرف على MaxQualityDetection. مثل NormalQuality ولكن بأعلى جودة[`DetectorSettings`](./detectorsettings). يسمح باكتشاف الرموز الشريطية التالفة والقطرية. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | عادي ضبط جودة التعرف على الجودة مسبقًا. مناسب لمعظم الباركود |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | يسمح للمحرك بالتعرف على الرموز الشريطية الملونة على خلفية ملونة كمسح إضافي. وضع بطيء للغاية. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | يسمح لمحرك Datamatrix بالتعرف على أكواد Datamatrix الشريطية الصناعية المتقطعة. الوضع البطيء الذي يساعد فقط في الرموز الشريطية المتقطعة التي تتكون من النقاط. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | يسمح للمحرك بالتعرف على الصورة المنخفضة كمسح إضافي. يتم تحديد الحجم المتناقص بواسطة خوارزميات المحرك الداخلية. يساعد الوضع على التعرف على الرموز الشريطية المشوشة وغير الواضحة ولكنها تم التقاطها بدقة عالية. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | للسماح للمحرك باستخدام الفجوة بين عمليات الفحص لزيادة سرعة التعرف. يمكن أن يتسبب الوضع في حدوث مشكلات في التعرف على الرموز الشريطية منخفضة الارتفاع. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | يسمح للمحرك بالتعرف على الرموز الشريطية التي تحتوي على مجموع اختباري غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الرموز الشريطية التالفة بنص غير صحيح. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | يسمح للمحرك بالتعرف على الصورة الملونة المعكوسة كمسح إضافي. يمكن استخدام الوضع عندما يكون الرمز الشريطي أبيض على خلفية سوداء. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | للسماح للمحرك بتمكين التجانس المتوسط كمسح إضافي. يساعد الوضع على التعرف على الرموز الشريطية المزعجة. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | يسمح لمحرك الباركود البريدي بالتعرف على الصور المشوشة قليلاً. يساعد الوضع على التعرف على الرموز الشريطية البريدية التالفة بشدة. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | يسمح لمحرك الباركود 1D بالتعرف بسرعة على الرموز الشريطية عالية الجودة التي تملأ الصورة بأكملها تقريبًا. الوضع يساعد على التعرف بسرعة على الرموز الشريطية التي تم إنشاؤها من الإنترنت. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | يسمح للمحرك للرموز الشريطية أحادية الأبعاد بالتعرف على الرموز الشريطية بأشرطة تم مسحها / لصقها في النمط. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | يسمح لمحرك QR / MicroQR بالتعرف على الرموز الشريطية MicroQR التالفة. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | يسمح للمحرك بالتعرف على الصورة العادية دون أي عمليات ترميم كمسح رئيسي. وضع للتعرف على الصورة كما هي. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | يسمح للمحرك بالتعرف على الرموز الشريطية بنوع ضوضاء الملح والورق. يمكن للوضع إزالة الضوضاء الصغيرة بنقاط بيضاء وسوداء. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | يسمح للمحرك بالتعرف على الصورة بدون بقع بيضاء صغيرة كمسح إضافي. يساعد الوضع على التعرف على الصورة المشوشة بالإضافة إلى تصفية التجانس المتوسطة. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | يسمح للمحرك بالتعرف على الرموز الشريطية أحادية الأبعاد مع المجموع الاختباري عن طريق التحقق من المزيد من متغيرات التعرف. القيمة الافتراضية: False . |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | إعدادات كاشف الباركود. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | يسمح لمحرك الباركود 1D بالتعرف بسرعة على الشريحة الوسطى من الصورة وإرجاع النتيجة دون استخدام أي خوارزميات تستغرق وقتًا طويلاً. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | حجم النافذة للتجانس المتوسط. القيم النموذجية هي 3 أو 4. القيمة الافتراضية هي 3. يجب تعيين AllowMedianSmoothing . |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | يسمح للمحرك بالتعرف على الرموز الشريطية الصغيرة على الصور الكبيرة. إذا تجاهلتها[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) تم تعيينه على صحيح. القيمة الافتراضية: False . |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | التبديل إلى كاشف الباركود القديم. |

### أمثلة

يوضح هذا النموذج كيفية استخدام QualitySettings مع BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // ضبط وضع الأداء العالي
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // يتم تعيين وضع الجودة العادي بشكل افتراضي
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // ضبط وضع الجودة العالية مع التعرف على السرعة المنخفضة 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // تعيين وضع الحد الأقصى للرموز الشريطية ، والذي يحاول العثور على جميع الرموز الشريطية الممكنة ، حتى لو كانت غير صحيحة. أبطأ وضع التعرف
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // ضبط وضع الأداء العالي
   reader.QualitySettings = QualitySettings.HighPerformance;
   // تعيين خيارات منفصلة
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // الوضع الافتراضي هو NormalQuality
   // تعيين خيارات منفصلة
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ضبط وضع الأداء العالي
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'يتم تعيين وضع الجودة العادي بشكل افتراضي
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'اضبط وضع الجودة العالية مع التعرف على السرعة المنخفضة
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'قم بتعيين أقصى وضع للباركود ، والذي يحاول العثور على جميع الرموز الشريطية الممكنة ، حتى لو كانت غير صحيحة. أبطأ وضع التعرف
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'ضبط وضع الأداء العالي
   reader.QualitySettings = QualitySettings.HighPerformance
   'ضع خيارات منفصلة
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'الوضع الافتراضي هو NormalQuality
   'ضع خيارات منفصلة
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
