---
title: Metered
second_title: Aspose.BarCode لمرجع .NET API
description: يوفر طرقًا لتعيين المفتاح الذي تم قياسه .
type: docs
weight: 1020
url: /ar/net/aspose.barcode/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح الذي تم قياسه .

```csharp
public class Metered
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Metered](metered)() | Default_Constructor |

## طُرق

| اسم | وصف |
| --- | --- |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey)(string, string) | مجموعات المفاتيح العامة والخاصة التي تم قياسها |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit)() | يحصل على ائتمان الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity)() | يحصل على حجم ملف الاستهلاك |

### أمثلة

في هذا المثال ، ستُبذل محاولة لتعيين المفتاح العام والخاص الذي تم قياسه

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode](../../aspose.barcode)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
