---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "enum. يحتوي على مستوى ثقة التعرف في C++."
type: docs
weight: 3500
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


يحتوي على مستوى ثقة التعرف

```cpp
enum class BarCodeConfidence : int32_t
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) ثقة الباركود حيث لم يتم التعرف على نص الرمز بشكل صحيح أو تم اكتشاف الباركود كاحتمال زائف |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) ثقة الباركود (معظمها باركودات أحادية الأبعاد) مع مجموع تحقق ضعيف أو حتى بدونها. قد يحتوي على بعض الأخطاء في نص الرمز أو حتى تعارفات زائفة إذا |

منخفض |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) ثقة تم تأكيدها باستخدام رموز BCH مثل Reed–Solomon. يجب ألا تكون هناك أخطاء في نص الرمز المقروء أو تعارفات زائفة |

## ملاحظات


يعرض هذا المثال كيف تغيرت BarCodeConfidence اعتمادًا على نوع الباركود
```cpp
[C#]
//ثقة متوسطة
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//ثقة قوية
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
