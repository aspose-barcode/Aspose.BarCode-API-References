---
title: "تعداد HanXinEncodeMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.Generation.HanXinEncodeMode enum. وضع ترميز رمز Han Xin. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode للأحرف Unicode"
type: docs
weight: 1360
url: /ar/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

وضع ترميز Han Xin Code. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode لأحرف Unicode.

```csharp
public enum HanXinEncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم ترميز أحرف Unicode باستخدام ترميز GB18030 وفقًا لمواصفات الباركود HanXin. |
| Binary | `1` | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | `2` | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع. |
| Unicode | `3` | يوفر وضع Unicode طريقة لتمثيل أي بيانات نصية بالإشارة إلى ترميز/مجموعة أحرف UTF8 في Han Xin Code. |
| URI | `4` | يشير وضع URI إلى أن البيانات الممثلة في Han Xin Code هي مرجع معرف الموارد الموحد (URI) وفقًا لـ RFC 3986. |
| Extended | `5` | وضع Extended يسمح بدمج أوضاع داخلية: Auto، Binary، Text، Numeric، URI، Unicode، ECI، Common Chinese Region One، Common Chinese Region Two، GB18030 Two Byte، GB18030 Four Byte. يمكن بناء Codetext يدويًا باستخدام البادئات والشرطة المائلة المزدوجة، على سبيل المثال: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" أو باستخدام HanXinExtCodetextBuilder. إذا كان Codetext يحتوي على جزء ECI، فإن الأوضاع التالية فقط يمكن أن تكون في ذلك Codetext بعد جزء ECI: Auto، Binary، Text، Numeric، URI، ECI. |

## أمثلة

```csharp
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

// استخدام HanXinExtCodetextBuilder لوضع Extended (نفس Codetext كما في المثال السابق)
//إنشاء نص شيفرة.
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

//توليد نص شيفرة.
var str = codeTextBuilder.GetExtendedCodetext();

//توليد.
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


