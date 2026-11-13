---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

معلمات DataMatrix.

يعرض نوع DataMatrixParameters الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| ecc_type | يحصل أو يعيّن نوع ECC لـ Datamatrix.<br/>            القيمة الافتراضية: DataMatrixEccType.Ecc200. |
| version | يحصل أو يعيّن حجم رمز Datamatrix.<br/>            القيمة الافتراضية: Version.Auto. |
| encode_mode | وضع الترميز لباركود Datamatrix.<br/>            القيمة الافتراضية: EncodeMode.Auto. |
| structured_append_barcode_id | معرّف الباركود لوضع Structured Append لباركود Datamatrix.<br/>            القيمة الافتراضية: 0 |
| structured_append_barcodes_count | عدد الباركودات لوضع Structured Append لباركود Datamatrix.<br/>            القيمة الافتراضية: 0 |
| structured_append_file_id | معرّف الملف لوضع Structured Append لباركود Datamatrix.<br/>            القيمة الافتراضية: 0 |
| is_reader_programming | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز<br/>            كبرمجة لتهيئة القارئ.<br/>            القيمة الافتراضية: false |
| macro_characters | تُستخدم قيم Macro Characters 05 و 06 للحصول على ترميز أكثر تكثيفًا في الأنماط الخاصة.<br/>            يمكن استخدامها فقط مع DataMatrixEccType.Ecc200 أو DataMatrixEccType.EccAuto.<br/>            لا يمكن استخدامها مع EncodeTypes.GS1DataMatrix<br/>            القيمة الافتراضية: MacroCharacters.None. |
| aspect_ratio | نسبة الارتفاع إلى العرض لوحدة باركود 2D. |
| eci_encoding | يحصل أو يضبط ترميز ECI. يستخدم عندما يكون EncodeMode على Auto.<br/>            القيمة الافتراضية: ISO-8859-1 |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

