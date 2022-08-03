---
title: Pdf417Parameters
second_title: Aspose.BarCode لمرجع .NET API
description: معلمات PDF417. يحتوي على معلمات PDF417 و MacroPDF417 و MicroPDF417. يتطلب MacroPDF417 حقلين Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المنظم مثل وضع MacroPDF417 حقلين Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.
type: docs
weight: 860
url: /ar/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

معلمات PDF417. يحتوي على معلمات PDF417 و MacroPDF417 و MicroPDF417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المنظم (مثل وضع MacroPDF417) حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.

```csharp
public class Pdf417Parameters
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | نسبة الارتفاع / العرض لوحدة الباركود ثنائية الأبعاد. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | كلمة كود الوظيفة لمحاكاة الكود 128. تطبق على MicroPDF417 فقط. تم التجاهل لأكواد PDF417 و MacroPDF417 الشريطية. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | الحصول على ترميز نص الترميز أو تعيينه. القيمة الافتراضية: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | عدد الأعمدة . |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | يستخدم لإرشاد القارئ لتفسير البيانات الواردة في الرمز كبرمجة لتهيئة القارئ. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417 نوع الترميز لوضع ضغط الرمز الشريطي . القيمة الافتراضية: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | معرفات تفسير القناة الموسعة. يتم استخدامه لإخبار قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لم يتم تطبيقه على حقول نص ماكرو PDF417 . التنفيذ الحالي يتكون من جميع ترميزات مجموعة الأحرف المعروفة. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | الحصول على أو تعيين نوع ترميز Pdf417 لمستوى تصحيح خطأ الباركود يتراوح من المستوى 0 إلى المستوى 8 ، المستوى 0 يعني عدم وجود معلومات تصحيح الخطأ ، المستوى 8 يعني أفضل تصحيح للخطأ مما يعني صورة أكبر . |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | MacroPdf417 اسم المرسل إليه الرمز الشريطي (حقل اختياري). اسم المرسل إليه الرمز الشريطي MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | المجموع الاختباري للرمز الشريطي MacroPdf417 (حقل اختياري) . المجموع الاختباري للرمز الشريطي MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) يحتوي حقل المجموع الاختباري على قيمة المجموع الاختباري لـ CRC 16 بت (2 بايت) باستخدام CCITT-16 متعدد الحدود. x ^ 16 + x ^ 12 + x ^ 5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | معرفات تفسير القناة الموسعة. يسري على الحقول النصية Macro PDF417 . |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | معرف ملف الباركود MacroPdf417 (حقل مطلوب) . معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الرمز الشريطي MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | حجم ملف MacroPdf417 (حقل اختياري) . حجم ملف MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بأكمله. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | معرف مقطع الباركود MacroPdf417 (حقل مطلوب) ، والذي يبدأ من 0 ، إلى MacroSegmentsCount - 1. معرف مقطع الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | MacroPdf417 عدد مقاطع الباركود (حقل اختياري) . عدد مقاطع الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | اسم مرسل الباركود MacroPdf417 (حقل اختياري). اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | ختم وقت الباركود MacroPdf417 (حقل اختياري). ختم وقت الرمز الشريطي MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | ما إذا كان نوع الترميز Pdf417 الخاص بالرمز الشريطي مقطوعًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. تتم إزالة مؤشر صف Rigth ونمط التوقف الأيمن في هذا الوضع. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | عدد الصفوف . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | إرجاع تمثيل سلسلة يمكن قراءته من قبل الإنسان[`Pdf417Parameters`](../pdf417parameters) . |

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
