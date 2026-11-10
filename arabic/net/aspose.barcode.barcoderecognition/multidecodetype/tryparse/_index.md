---
title: "MultiDecodeType.TryParse"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "طريقة MultiDecodeType. تقوم بتحويل تمثيل السلسلة النصية لـ MultiDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أم فشل."
type: docs
weight: 110
url: /ar/net/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType.TryParse method

يحوّل تمثيل السلسلة النصية لـ MultiDecodeType إلى مثيله. تُشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل ناجحة أم فاشلة.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | String | سلسلة نصية بالتنسيق إما "AllSupportedTypes" أو "EAN8,EAN13,CodaBar" للتحويل. |
| result | MultiDecodeType& | يتم إرجاع MultiDecodeType فعلي عندما يكتمل التحويل بنجاح؛ |

### قيمة الإرجاع

**true** if s was converted successfully; otherwise, **false**.

### انظر أيضًا

* class [MultiDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


