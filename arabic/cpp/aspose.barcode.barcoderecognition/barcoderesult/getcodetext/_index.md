---
title: "طريقة"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على نص الكود مع الترميز في C++."
type: docs
weight: 1000
url: /ar/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


يحصل على نص الشيفرة مع الترميز.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| الترميز | System::SharedPtr\<System::Text::Encoding\> | الترميز لنص الكود. |

### ReturnValue

سلسلة تحتوي على نص الكود المعترف به.
## ملاحظات



هذا المثال يوضح كيفية استخدام **GetCodeText**:


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## انظر أيضًا

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
