---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes للغة Python عبر .NET API Reference"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

وضع ترميز Han Xin Code. يُنصح باستخدام الوضع التلقائي مع أحرف ASCII / الصينية أو Unicode لأحرف Unicode.

## Members
| اسم العضو | الوصف |
| :- | :- |
| AUTO | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            يتم ترميز الأحرف Unicode باستخدام ترميز GB18030 وفقًا لمواصفات باركود HanXin. |
| BINARY | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. <br/>            إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI.<br/>            إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار في ECI، يتم إلقاء استثناء.<br/>            يرجى ملاحظة أن بعض الماسحات القديمة (قبل 2006) قد لا تدعم هذا الوضع. |
| UNICODE | يوفر وضع Unicode طريقة لتمثيل أي بيانات نصية بالإشارة إلى ترميز/مجموعة أحرف UTF8 في رمز Han Xin. |
| URI | يشير وضع URI إلى أن البيانات الممثلة في رمز Han Xin هي معرف مورد موحد (URI)<br/>            إشارة إلى RFC 3986. |
| EXTENDED | يسمح وضع Extended بدمج أوضاع داخلية: Auto، Binary، Text، Numeric، URI، Unicode، ECI، Common Chinese Region One،<br/>            Common Chinese Region Two، GB18030 Two Byte، GB18030 Four Byte.<br/>            يمكن بناء Codetext يدويًا باستخدام البوادئ والشرطتين المائلتين المزدوجتين، مثال: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" أو باستخدام HanXinExtCodetextBuilder.<br/>            إذا كان Codetext يحتوي على جزء ECI، فإن الأوضاع التالية فقط يمكن أن تكون في ذلك Codetext بعد جزء ECI:<br/>            Auto، Binary، Text، Numeric، URI، ECI. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

