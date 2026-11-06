---
title: "enum"
linktitle: "ترميزات ECI"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 6600
url: /ar/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ISO_8859_1 | 3 | ترميز ISO/IEC 8859-1 للأبجدية اللاتينية رقم 1. معرف ECI:"\000003" |
| ISO_8859_2 | 4 | ترميز ISO/IEC 8859-2 للأبجدية اللاتينية رقم 2. معرف ECI:"\000004" |
| ISO_8859_3 | 5 | ترميز ISO/IEC 8859-3 للأبجدية اللاتينية رقم 3. معرف ECI:"\000005" |
| ISO_8859_4 | 6 | ترميز ISO/IEC 8859-4 للأبجدية اللاتينية رقم 4. معرف ECI:"\000006" |
| ISO_8859_5 | 7 | ترميز ISO/IEC 8859-5 للأبجدية اللاتينية/السيريلية. معرف ECI:"\000007" |
| ISO_8859_6 | 8 | ترميز ISO/IEC 8859-6 للأبجدية اللاتينية/العربية. معرف ECI:"\000008" |
| ISO_8859_7 | 9 | ترميز ISO/IEC 8859-7 للأبجدية اللاتينية/اليونانية. معرف ECI:"\000009" |
| ISO_8859_8 | 10 | ترميز ISO/IEC 8859-8 للأبجدية اللاتينية/العبرية. معرف ECI:"\000010" |
| ISO_8859_9 | 11 | ترميز ISO/IEC 8859-9 للأبجدية اللاتينية رقم 5. معرف ECI:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 ترميز أبجدية لاتينية رقم 6. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 ترميز أبجدية لاتينية/تايلاندية. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 ترميز أبجدية لاتينية رقم 7 (حافة البلطيق). ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 ترميز أبجدية لاتينية رقم 8 (سلتية). ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 ترميز أبجدية لاتينية رقم 9. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 ترميز أبجدية لاتينية رقم 10. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 ملحق 1 + JIS X 0201) ترميز. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 لاتينية 2 (وسط أوروبا) ترميز. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 سيريلية ترميز. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 لاتينية 1 ترميز. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 عربية ترميز. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (البايت الأعلى أولاً) ترميز. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 ترميز UTF-8. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 النسخة المرجعية الدولية لمجموعة أحرف ISO المشفرة بـ 7 بت ترميز. ECI Id:"\000027" |
| Big5 | 28 | ترميز مجموعة الأحرف الصينية Big 5 (Taiwan). معرف ECI Id:\"\\000028\" |
| GB2312 | 29 | ترميز مجموعة الأحرف الصينية GB2312. معرف ECI Id:\"\\000029\" |
| EUC_KR | 30 | ترميز مجموعة الأحرف الكورية. معرف ECI Id:\"\\000030\" |
| GBK | 31 | ترميز GBK (امتداد لـ GB2312 للغة الصينية المبسطة). معرف ECI Id:\"\\000031\" |
| GB18030 | 32 | ترميز مجموعة الأحرف الصينية GGB18030. معرف ECI Id:\"\\000032\" |
| UTF16LE | 33 | ترميز ISO/IEC 10646 UTF-16LE. معرف ECI Id:\"\\000033\" |
| UTF32BE | 34 | ترميز ISO/IEC 10646 UTF-32BE. معرف ECI Id:\"\\000034\" |
| UTF32LE | 35 | ترميز ISO/IEC 10646 UTF-32LE. معرف ECI Id:\"\\000035\" |
| INVARIANT | 170 | ISO/IEC 646: مجموعة الأحرف المشفرة 7-بت ISO - ترميز مجموعة الأحرف الثابتة. معرف ECI Id:\"\\000170\" |
| BINARY | 899 | بيانات ثنائية 8-بت. معرف ECI Id:\"\\000899\" |
| NONE | 0 | لا تفسير قناة موسعة |

## ملاحظات


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز.

يعرض هذا المثال كيفية استخدام ترميز ECI وحفظ صورة [BarCode](../../aspose.barcode/).
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = "12345TEXT"
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
        generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
        generator.Save("test.png")
    End Using
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
