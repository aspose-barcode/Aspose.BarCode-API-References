---
title: "Aspose::BarCode::Metered فئة"
linktitle: "مقاس"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Metered فئة. يوفر طرقًا لتعيين مفتاح المقاس في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode/metered/
---
## Metered class


يوفر طرقًا لتعيين المفتاح القائم على العداد.

```cpp
class Metered : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |
| [GetProductName](./getproductname/)() | يحصل على اسم المنتج المرخص |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | تحقق مما إذا كان المقاس مرخصًا |
| [Metered](./metered/)() | يُهيئ نسخة جديدة من هذه الفئة. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | يضبط المفتاح العام والخاص للمقاس. إذا قمت بشراء ترخيص مقاس، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً يكون هذا كافيًا. ومع ذلك، إذا فشل دائمًا رفع بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم، لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
## ملاحظات


في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص للمقاس

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> ملف jar للمكوّن:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## انظر أيضًا

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
