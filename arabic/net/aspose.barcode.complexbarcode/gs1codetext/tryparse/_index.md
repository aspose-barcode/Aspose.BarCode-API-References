---
title: "GS1Codetext.TryParse"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "GS1Codetext method. يحاول تحليل سلسلة عنصر GS1 محاط بالأقواس بالشكل AIvalueAIvalue ويعيد أخطاء تحقق منظمة. يجب كتابة حرف حرفي  داخل القيمة كـ  لا يتم دعم أي تسلسل هروب آخر ولا يتطلب  الهروب."
type: docs
weight: 140
url: /ar/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

يحاول تحليل سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value ويعيد أخطاء تحقق منظمة. يجب كتابة '(' حرفيًا داخل قيمة كـ \\(; لا يتم دعم أي تسلسل هروب آخر، ولا يتطلب ')' الهروب.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | String | سلسلة عنصر GS1 محاط بالأقواس للتحليل. |
| result | GS1Codetext& | عند إرجاع هذه الطريقة true، تحتوي على نص GS1 المحلل؛ وإلا تكون null. |
| validationResult | GS1ValidationResult& | يحتوي على نتيجة التحقق، أو null عندما تكون *value* null. |

### قيمة الإرجاع

True عندما ينجح التحليل؛ وإلا false.

### انظر أيضًا

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


