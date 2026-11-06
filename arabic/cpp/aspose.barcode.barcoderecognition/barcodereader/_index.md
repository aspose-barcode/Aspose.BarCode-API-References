---
title: "الفئة Aspose::BarCode::BarCodeRecognition::BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "الفئة Aspose::BarCode::BarCodeRecognition::BarCodeReader. يقوم BarCodeReader بتغليف صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Abort](./abort/)() | تطلب الدالة إنهاء جلسة التعرف الحالية من خيط آخر. Abort هي طريقة لا يمكن إلغاء حظرها وتعيد التحكم فور استدعائها. يجب استخدام هذه الطريقة عندما تكون عملية التعرف طويلة جدًا. |
| [BarCodeReader](./barcodereader/)() | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./) بالقيم الافتراضية. يتطلب تعيين الصورة (SetBitmapImage()) قبل استدعاء طريقة [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./) من صورة. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./) من ملف. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | ينشئ مثيلًا جديدًا من الفئة [BarCodeReader](./) من إطار سطوع. |
| [Dispose](./dispose/)() override | تحرير المورد |
| [ExportToXml](./exporttoxml/)(System::String) | يصدّر خصائص [BarCode](../../aspose.barcode/) إلى ملف XML المحدد |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | يصدّر خصائص [BarCode](../../aspose.barcode/) إلى تدفق XML المحدد |
| [get_BarCodeReadType](./get_barcodereadtype/)() | يحصل على نوع فك ترميز الباركود المستخدم للتعرف. يجب تعيينه قبل استدعاء [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | معلمات فك الترميز الرئيسية لـ [BarCode](../../aspose.barcode/). يحتوي على معلمات تؤثر على البيانات المعترف بها. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | يحصل على مصفوفة [BarCodeResult](../barcoderesult/) المعترف بها |
| [get_FoundCount](./get_foundcount/)() | يحصل على عدد الباركودات المعترف بها |
| static [get_ProcessorSettings](./get_processorsettings/)() | يحصل على إعدادات استخدام نوى المعالج. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) يسمح بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد [QualitySettings](../qualitysettings/) بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لـ [QualitySettings](../qualitysettings/) هي NormalQuality. |
| [get_Timeout](./get_timeout/)() | يحصل على مهلة عملية التعرف بالمللي ثانية. |
| static [ImportFromXml](./importfromxml/)(System::String) | يستورد خصائص [BarCode](../../aspose.barcode/) من ملف XML المحدد ويطبقها على مثيل [BarCodeReader](./) الحالي. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | يستورد خصائص [BarCode](../../aspose.barcode/) من تدفق XML المحدد ويطبقها على مثيل [BarCodeReader](./) الحالي. |
| [ReadBarCodes](./readbarcodes/)() | يقرأ [BarCodeResult](../barcoderesult/)s من الصورة. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | يضبط نوع فك تشفير الباركود المستخدم للتعرف. يجب ضبطه قبل استدعاء [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) يسمح بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد [QualitySettings](../qualitysettings/) بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لـ [QualitySettings](../qualitysettings/) هي NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | يضبط مهلة عملية التعرف بالمللي ثانية. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | يضبط صورة bitmap للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | يضبط صورة bitmap والمناطق للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | يضبط صورة bitmap والمنطقة للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | يضبط ملف الصورة للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | يضبط تدفق الصورة للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | يضبط إطار الإضاءة والمنطقة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | يضبط إطار الإضاءة والمناطق للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | يضبط إطار الإضاءة للتعرف. يجب استدعاؤه قبل طريقة [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | يضبط مصفوفة الأنواع [SingleDecodeType](../singledecodetype/) للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](./readbarcodes/). |
## ملاحظات


يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
