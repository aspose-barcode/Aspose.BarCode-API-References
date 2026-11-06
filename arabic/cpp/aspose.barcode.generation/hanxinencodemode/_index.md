---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " تعداد. وضع ترميز رمز Han Xin. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode لأحرف Unicode في C++."
type: docs
weight: 6900
url: /ar/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


وضع ترميز Han Xin Code. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode للأحرف Unicode.

```cpp
enum class HanXinEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم ترميز أحرف Unicode باستخدام ترميز GB18030 وفقًا لمواصفات الباركود HanXin. |
| ثنائي | 1 | في وضع الثنائي، يتم ترميز CodeText بأقصى ضغط للبيانات. إذا تم العثور على حرف Unicode، يتم رفع استثناء. |
| ECI | 2 | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. يرجى ملاحظة أن بعض الماسحات (قبل 2006) قد لا تدعم هذا الوضع. |
| Unicode | 3 | يوفر وضع Unicode طريقة لتمثيل أي بيانات نصية بالإشارة إلى ترميز/مجموعة أحرف UTF8 في رمز Han Xin. |
| URI | 4 | يشير وضع URI إلى أن البيانات الممثلة في رمز Han Xin هي معرف مورد موحد (URI) وفقًا للمرجع RFC 3986. |
| Extended | 5 | وضع Extended يسمح بدمج أوضاع داخلية: Auto، Binary، Text، Numeric، URI، Unicode، ECI، [Common](../../aspose.barcode.common/) Chinese Region One، [Common](../../aspose.barcode.common/) Chinese Region Two، GB18030 Two Byte، GB18030 Four Byte. يمكن بناء النص المشفر يدويًا باستخدام البوادئ والشرطة المائلة المزدوجة، مثال: ":abc\000009:ΑΒΓΔΕ:ab\c" أو باستخدام [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). إذا كان النص المشفر يحتوي على جزء ECI، فإن الأوضاع التالية فقط يمكن أن تكون في ذلك النص بعد جزء ECI: Auto، Binary، Text، Numeric، URI، ECI. |

## ملاحظات



```cpp
[C#]
// وضع Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// وضع Binary
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// وضع ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// وضع Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// وضع URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// وضع Extended
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// استخدام HanXinExtCodetextBuilder لوضع Extended (نفس النص المشفر كما في المثال السابق)
//إنشاء نص مشفر
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//توليد نص مشفر
var str = codeTextBuilder.GetExtendedCodetext();

//توليد
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
