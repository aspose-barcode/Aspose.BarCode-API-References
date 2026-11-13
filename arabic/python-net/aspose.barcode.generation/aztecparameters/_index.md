---
title: "AztecParameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

معلمات Aztec.

نوع AztecParameters يعرض الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| encode_mode | يحصل أو يضبط وضع ترميز Aztec. <br/>            القيمة الافتراضية: Auto. |
| eci_encoding | يحصل أو يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto.<br/>            القيمة الافتراضية: ISO-8859-1 |
| structured_append_barcode_id | معرّف الباركود لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركودات.<br/>            القيمة الافتراضية: 0 |
| structured_append_barcodes_count | عدد الباركودات لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26.<br/>            القيمة الافتراضية: 0 |
| structured_append_file_id | معرّف الملف لوضع الإلحاق المُنظم لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات.<br/>            القيمة الافتراضية: سلسلة فارغة |
| error_level | مستوى تصحيح الأخطاء لأنواع باركود Aztec.<br/>            يجب أن تكون القيمة بين 5 و 95. |
| symbol_mode | يحصل على أو يعيّن وضع رمز Aztec.<br/>            القيمة الافتراضية: AztecSymbolMode.Auto. |
| layers_count | يحصل على أو يعيّن عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 لوضع Compact و<br/>            في النطاق من 1 إلى 32 لوضع Full Range.<br/>            القيمة الافتراضية: 0 (تلقائي). |
| is_reader_initialization | يُستخدم لتوجيه القارئ لتفسير البيانات الموجودة داخل الرمز<br/>            كبرمجة لتهيئة القارئ. |
| aspect_ratio | نسبة الارتفاع إلى العرض لوحدة باركود 2D. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

