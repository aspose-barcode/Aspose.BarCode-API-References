---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز USA Driving License PDF417.

يعرض نوع USADriveIdCodetext الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| USADriveIdCodetext() | يُنشئ مثيلاً جديدًا لفئة USADriveIdCodetext |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| issuer_identification_number | هذا الرقم يحدد بشكل فريد <br/>            الولاية الصادرة ويمكن الحصول عليه عن طريق الاتصال بسلطة الإصدار ISO<br/>            (AAMVA). يجب ترميز الرقم الكامل المكوّن من 6 أرقام IIN. |
| aamva_version_number | رقم إصدار AAMVA 00-99 |
| jurisdiction_version_number | رقم إصدار الولاية القضائية 00-99 |
| number_of_entries | عدد 00-99 من الملفات الفرعية |
| subfile_designator | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. <br/>            مهم: إذا تم ضبط النوع فقط، سيتم ضبط الإزاحة والطول تلقائيًا. |
| mandatory_elements | العناصر الإلزامية (الحقول) للبطاقة |
| optional_elements | العناصر الاختيارية (الحقول) للبطاقة |
| jurisdiction_specific_subfile | حقول خاصة بالولاية القضائية |
## الطرق
| الاسم | الوصف |
| :- | :- |
| get_constructed_codetext() | Construct codetext from USA DL data |
| init_from_string(constructed_codetext) | Initialize USA DL object from codetext |
| get_barcode_type() | يعيد نوع الباركود لـ USA DL (Pdf417) |
| save_to_xml(stream) | يحفظ إلى XML |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

