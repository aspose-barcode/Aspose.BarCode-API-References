---
title: BarCodeReader
second_title: Aspose.BarCode لمرجع .NET API
description: يقوم BarCodeReader بتغليف صورة قد تحتوي على واحد أو أكثر من الرموز الشريطية  ثم يمكنه إجراء عملية ReadBarCodes لاكتشاف الرموز الشريطية.
type: docs
weight: 60
url: /ar/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

يقوم BarCodeReader بتغليف صورة قد تحتوي على واحد أو أكثر من الرموز الشريطية ، ثم يمكنه إجراء عملية ReadBarCodes لاكتشاف الرموز الشريطية.

```csharp
public class BarCodeReader : Component
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة مع القيم الافتراضية . يتطلب تعيين الصورة (SetBitmapImage ()) قبل استدعاء طريقة ReadBarCodes (). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة من صورة. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_11)(string) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة من ملف . |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../barcodereader) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | معلمات فك الشفرة الرئيسية. يحتوي على معلمات تؤثر على البيانات المعترف بها. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | يحصل على الاعتراف[`BarCodeResult`](../barcoderesult)مجموعة ق |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | يتم التعرف على عدد الرموز الشريطية |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings تسمح بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد QualitySettings بسرعة من خلال الإعدادات المسبقة المضمنة: HighPerformance ، NormalQuality ، HighQuality ، MaxBarCodes أو يمكنك تكوين خيارات منفصلة يدويًا . القيمة الافتراضية لإعدادات الجودة هي NormalQuality . |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | الحصول على أو تعيين مهلة عملية التعرف بالمللي ثانية. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | الحصول على إعدادات استخدام نوى المعالج. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | يستورد خصائص BarCode من xml-stream المحدد ويطبقها على مثيل BarCodeReader الحالي. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | يستورد خصائص BarCode من ملف xml المحدد ويطبقها على نسخة BarCodeReader الحالية. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | تطلب الوظيفة إنهاء جلسة التعرف الحالية من مؤشر ترابط آخر. الإحباط هو طريقة غير قابلة للفتح ويعيد التحكم بعد الاتصال مباشرة. يجب استخدام الطريقة عندما تكون عملية التعرف طويلة جدًا. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | تصدير خصائص BarCode إلى xml-Stream المحدد |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | تصدير خصائص BarCode إلى ملف xml المحدد |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | يقرأ[`BarCodeResult`](../barcoderesult) الصورة من الصورة. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | يضبط صورة نقطية للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | يضبط دفق الصورة للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | تعيين ملف الصورة للتعرف عليه. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | يضبط صورة نقطية ومنطقة للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | يضبط الصورة النقطية ومناطق التعرف. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | يحدد نوع فك التشفير للتعرف عليه. يجب استدعاء قبل أسلوب ReadBarCodes (). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | مجموعات [`SingleDecodeType`](../singledecodetype) اكتب مجموعة للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes (). |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
