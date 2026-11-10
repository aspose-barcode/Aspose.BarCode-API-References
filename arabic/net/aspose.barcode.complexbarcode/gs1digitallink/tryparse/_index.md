---
title: "GS1DigitalLink.TryParse"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "طريقة GS1DigitalLink. تحاول تحليل URI رابط GS1 الرقمي غير المضغوط وتُرجع أخطاء تحقق مُنظمة."
type: docs
weight: 190
url: /ar/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

يحاول تحليل URI رابط GS1 الرقمي غير المضغوط ويعيد أخطاء تحقق منظمة.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | String | URI رابط GS1 الرقمي للتحليل. |
| result | GS1DigitalLink& | عند إرجاع هذه الطريقة true، تحتوي على رابط GS1 الرقمي المُحلل؛ وإلا تكون null. |
| validationResult | GS1ValidationResult& | يحتوي على نتيجة التحقق، أو null عندما تكون *value* null. |

### قيمة الإرجاع

True عندما ينجح التحليل؛ وإلا false.

### انظر أيضًا

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


