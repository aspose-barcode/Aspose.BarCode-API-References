---
title: "الفئة USADriveIdCodetext"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.USADriveIdCodetext. فئة لتشفير وفك تشفير النص المضمن في رمز رخصة القيادة الأمريكية PDF417"
type: docs
weight: 810
url: /ar/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز رخصة القيادة الأمريكية PDF417.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | رقم إصدار AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | هذا الرقم يحدد بشكل فريد الولاية الصادرة ويمكن الحصول عليه عن طريق الاتصال بسلطة الإصدار ISO (AAMVA). يجب ترميز رقم التعريف المؤسسي (IIN) الكامل المكوّن من 6 أرقام. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | حقول خاصة بالولاية |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | رقم إصدار الولاية 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | العناصر (الحقول) الإلزامية للبطاقة |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | عدد 00-99 من الملفات الفرعية |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | العناصر (الحقول) الاختيارية للبطاقة |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. مهم: قم بتعيين النوع فقط، سيتم تعيين الإزاحة والطول تلقائيًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | يعيد نوع الباركود لبطاقة رخصة القيادة الأمريكية (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | إنشاء نص الكود من بيانات رخصة القيادة الأمريكية |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | تهيئة كائن رخصة القيادة الأمريكية من نص الكود |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | يحفظ إلى XML |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | العناصر (الحقول) الإلزامية للبطاقة |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | العناصر (الحقول) الاختيارية للبطاقة |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | خصائص ملف فرعي USA DL، الإزاحة والطول يتم تعيينها تلقائيًا. |

### انظر أيضًا

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


