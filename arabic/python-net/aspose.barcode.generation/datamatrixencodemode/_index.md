---
title: "DataMatrixEncodeMode"
second_title: "Aspose.Sildes للغة Python عبر .NET API Reference"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

وضع الترميز لمُشفر DataMatrix، الافتراضي Auto

## Members
| اسم العضو | الوصف |
| :- | :- |
| AUTO | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            يتم إعادة ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار في ECI، يتم إلقاء استثناء. |
| ASCII | يقوم بترميز حرف أبجدي رقمي واحد أو حرفين رقميين لكل بايت |
| C40 | يستخدم ترميز C40. يقوم بترميز الأحرف الأبجدية الرقمية الكبيرة، الأحرف الصغيرة والرموز الخاصة |
| TEXT | يستخدم ترميز Text. يقوم بترميز الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة |
| EDIFACT | يستخدم ترميز EDIFACT. يستخدم ست بتات لكل حرف، يقوم بترميز الأرقام، الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة. |
| ANSIX12 | يستخدم ترميز ANSI X12. |
| EXTENDED |  |
| BASE256 | يقوم بترميز قيم 8 بت |
| BINARY | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار في ECI، يتم إلقاء استثناء.<br/>            يرجى ملاحظة أن بعض الماسحات القديمة (قبل 2006) قد لا تدعم هذا الوضع. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

