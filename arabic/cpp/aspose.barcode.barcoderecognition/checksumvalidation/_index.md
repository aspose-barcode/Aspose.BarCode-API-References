---
title: "enum"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 3300
url: /ar/cpp/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enum




```cpp
enum class ChecksumValidation
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| افتراضي | 0 | إذا كان المجموع الاختباري مطلوبًا وفقًا للمواصفة - سيتم التحقق منه. |
| تشغيل | 1 | تحقق دائمًا من المجموع الاختباري إذا كان ذلك ممكنًا. |
| إيقاف | 2 | لا تتحقق من المجموع الاختباري. |

## ملاحظات


تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريدية.

يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وكـ لا حيث يكون المجموع الاختباري ممكنًا فقط.

المجموع الاختباري لا يُستخدم أبدًا: Codabar, PatchCode, Pharmacode, DataLogic2of5

المجموع الاختباري ممكن: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

المجموع الاختباري يُستخدم دائمًا: باقي الرموز

يعرض هذا المثال تأثير ChecksumValidation على جودة التعرف والنتائج
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //المجموع الاختباري معطل
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //المجموع الاختباري مفعّل
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
