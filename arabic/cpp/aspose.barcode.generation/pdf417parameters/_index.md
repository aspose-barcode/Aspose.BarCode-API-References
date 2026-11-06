---
title: "Aspose::BarCode::Generation::Pdf417Parameters فئة"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::Pdf417Parameters فئة. معلمات PDF417. يحتوي على معلمات PDF417 وMacroPDF417 وMicroPDF417 وGS1MicroPdf417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID وPdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع Structured Append (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID وPdf417MacroSegmentID. جميع الحقول الأخرى اختيارية في C++."
type: docs
weight: 4000
url: /ar/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


معلمات PDF417. تحتوي على معلمات PDF417، MacroPDF417، MicroPDF417 و GS1MicroPdf417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المنظم (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.

```cpp
class Pdf417Parameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [get_Columns](./get_columns/)() const | عدد الأعمدة. |
| [get_ECIEncoding](./get_eciencoding/)() const | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. يتكون التنفيذ الحالي من جميع ترميزات مجموعة الأحرف المعروفة. |
| [get_EncodeMode](./get_encodemode/)() const | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء في [BarCode](../../aspose.barcode/) والذي يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح الأخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [get_IsLinked](./get_islinked/)() const | يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم تشفير الأوضاع 906 و907 و912 و913 و914 و915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [get_MacroCharacters](./get_macrocharacters/)() const | تُستخدم قيم Macro Characters 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع 916 و917 الخاصة بـ MicroPdf417. القيمة الافتراضية: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | اسم المستلم لباركود MacroPdf417 (حقل اختياري). اسم المستلم لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | مجموع تحقق (checksum) لباركود MacroPdf417 (حقل اختياري). مجموع تحقق لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع تحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT‑16. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | معرّف ملف باركود MacroPdf417 (حقل مطلوب). معرّف ملف باركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | اسم ملف باركود MacroPdf417 (حقل اختياري). اسم ملف باركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | معرّف الجزء لباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرّف الجزء لباركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | عدد أجزاء باركود MacroPdf417 (حقل اختياري). عدد أجزاء باركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | اسم المرسل لباركود MacroPdf417 (حقل اختياري). اسم المرسل لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | الطابع الزمني لباركود MacroPdf417 (حقل اختياري). الطابع الزمني لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [get_Rows](./get_rows/)() const | عدد الصفوف. |
| [get_Truncate](./get_truncate/)() const | ما إذا كان نوع ترميز Pdf417 في [BarCode](../../aspose.barcode/) مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع. |
| [set_AspectRatio](./set_aspectratio/)(float) | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [set_Columns](./set_columns/)(int32_t) | عدد الأعمدة. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. يتكون التنفيذ الحالي من جميع ترميزات مجموعة الأحرف المعروفة. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء الخاص بـ [BarCode](../../aspose.barcode/) الذي يتراوح من المستوى0 إلى المستوى8، حيث يعني المستوى0 عدم وجود معلومات تصحيح الأخطاء، ويعني المستوى8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم تشفير الأوضاع 906 و907 و912 و913 و914 و915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | تُستخدم قيم Macro Characters 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع 916 و917 الخاصة بـ MicroPdf417. القيمة الافتراضية: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). اسم المستلم لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | مجموع تحقق (checksum) لباركود MacroPdf417 (حقل اختياري). مجموع تحقق لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع تحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT‑16. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | معرّف ملف باركود MacroPdf417 (حقل مطلوب). معرّف ملف باركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | اسم ملف باركود MacroPdf417 (حقل اختياري). اسم ملف باركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | معرّف الجزء لباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرّف الجزء لباركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | عدد أجزاء باركود MacroPdf417 (حقل اختياري). عدد أجزاء باركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | اسم المرسل لباركود MacroPdf417 (حقل اختياري). اسم المرسل لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | الطابع الزمني لباركود MacroPdf417 (حقل اختياري). الطابع الزمني لباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | عدد الصفوف. |
| [set_Truncate](./set_truncate/)(bool) | ما إذا كان نوع ترميز Pdf417 في [BarCode](../../aspose.barcode/) مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع. |
| [ToString](./tostring/)() const override | يعيد تمثيل سلسلة قابل للقراءة من قبل الإنسان لهذا [Pdf417Parameters](./). |
## ملاحظات


تظهر هذه الأمثلة كيفية ترميز أوضاع UCC/EAN-128 غير المرتبطة في GS1MicroPdf417
```cpp
[C#]
//يقوم بترميز وضع GS1 UCC/EAN-128 غير المرتبط 905 مع AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//يقوم بترميز أوضاع GS1 UCC/EAN-128 غير المرتبطة 903، 904 مع أي AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
