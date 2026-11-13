---
title: "QREncodeMode"
second_title: "Aspose.Sildes للغة Python عبر .NET API Reference"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

وضع الترميز لباركودات QR.

## Members
| اسم العضو | الوصف |
| :- | :- |
| AUTO | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            يتم ترميز أحرف Unicode في وضع kanji إذا أمكن، أو يتم إعادة ترميزها باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المحدد، يتم إلقاء استثناء. |
| EXTENDED |  |
| BINARY | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المحدد، يتم إلقاء استثناء.<br/>            يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع.<br/>            هذا الوضع غير مدعوم من قبل رموز MicroQR. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

