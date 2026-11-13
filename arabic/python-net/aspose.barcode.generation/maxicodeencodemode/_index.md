---
title: "MaxiCodeEncodeMode"
second_title: "Aspose.Sildes للغة Python عبر .NET API Reference"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

وضع الترميز لباركودات MaxiCode.

## Members
| اسم العضو | الوصف |
| :- | :- |
| AUTO | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            يتم إعادة ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار في ECI، يتم إلقاء استثناء. |
| EXTENDED |  |
| BINARY | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار في ECI، يتم إلقاء استثناء.<br/>            يرجى ملاحظة أن بعض الماسحات القديمة (قبل 2006) قد لا تدعم هذا الوضع. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

