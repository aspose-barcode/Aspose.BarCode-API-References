---
title: "فئة Aspose::BarCode::Generation::HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام فئة Aspose::BarCode::Generation::HanXinExtCodetextBuilder في C++."
type: docs
weight: 2800
url: /ar/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | يضيف جزء نص الترميز في الوضع التلقائي |
| [AddBinary](./addbinary/)(System::String) | يضيف جزء نص الترميز في الوضع الثنائي |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | يضيف جزء نص الترميز في وضع [Common](../../aspose.barcode.common/) المنطقة الصينية الأولى |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | يضيف جزء نص الترميز في وضع [Common](../../aspose.barcode.common/) المنطقة الصينية الثانية |
| [AddECI](./addeci/)(System::String, int32_t) | يضيف جزء نص الترميز في وضع ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | يضيف جزء نص الترميز في وضع GB18030 بأربعة بايت |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | يضيف جزء نص الترميز في وضع GB18030 بايتين |
| [AddNumeric](./addnumeric/)(System::String) | يضيف جزء نص الترميز في الوضع الرقمي |
| [AddText](./addtext/)(System::String) | يضيف جزء نص الترميز في وضع النص |
| [AddUnicode](./addunicode/)(System::String) | يضيف جزء نص الترميز في وضع Unicode |
| [AddURI](./adduri/)(System::String) | يضيف جزء نص الترميز في وضع URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | يرجع نص الترميز من مُنشئ نص الترميز في الوضع الموسع |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## ملاحظات


مولد نص الترميز الموسع لرمز Han Xin للوضع الموسع من EncodeMode


```cpp
[C#]
//وضع النص المشفر الموسع
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

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//توليد نص مشفر
var str = codeTextBuilder.GetExtendedCodetext();

//توليد
using (var bg = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    bg.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    var img = bg.GenerateBarCodeImage();
    using (var r = new BarCodeReader(img, DecodeType.HanXin))
     {
        var found = r.ReadBarCodes();
        Assert.AreEqual(1, found.Length);
        Assert.AreEqual(expectedStr, found[0].CodeText);
      }
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
