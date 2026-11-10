---
title: "GS1DigitalLink.Create"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "طريقة GS1DigitalLink. تُنشئ رابطًا رقميًا GS1 عن طريق نسخ جميع العناصر من نص كود GS1 واختيار المفتاح الأساسي المتاح الوحيد"
type: docs
weight: 20
url: /ar/net/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## Create(string, GS1Codetext) {#create}

ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واختيار المفتاح الأساسي المتاح الوحيد.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| uriStem | String | بادئة URI مطلقة HTTP أو HTTPS قبل المفتاح الأساسي. |
| codetext | GS1Codetext | نص شفرة GS1 الذي تم نسخ عناصره. |

### قيمة الإرجاع

رابط GS1 الرقمي يحتوي على العناصر المنسوخة.

### انظر أيضًا

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)

---

## Create(string, GS1Codetext, string) {#create_1}

ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واستخدام المفتاح الأساسي المحدد.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext, 
    string primaryApplicationIdentifier)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| uriStem | String | بادئة URI مطلقة HTTP أو HTTPS قبل المفتاح الأساسي. |
| codetext | GS1Codetext | نص شفرة GS1 الذي تم نسخ عناصره. |
| primaryApplicationIdentifier | String | المفتاح الرئيسي AI. |

### قيمة الإرجاع

رابط GS1 الرقمي يحتوي على العناصر المنسوخة.

### انظر أيضًا

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


