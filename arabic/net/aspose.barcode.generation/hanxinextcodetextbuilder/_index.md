---
title: "الفئة HanXinExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.Generation.HanXinExtCodetextBuilder. مولد نص رمزي موسع لرمز Han Xin للوضع الموسع من EncodeMode"
type: docs
weight: 1380
url: /ar/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

مولد نص رمزي موسع لرمز Han Xin للوضع الموسع من EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | يضيف جزء نص رمزي في الوضع التلقائي |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | يضيف جزء نص رمزي في الوضع الثنائي |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | يضيف جزء نص رمزي في وضع المنطقة الصينية المشتركة الأولى |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | يضيف جزء نص رمزي في وضع المنطقة الصينية المشتركة الثانية |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | يضيف جزء نص رمزي في وضع ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | يضيف جزء نص رمزي في وضع GB18030 بأربعة بايت |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | يضيف جزء نص رمزي في وضع GB18030 بايتين |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | يضيف جزء نص رمزي في الوضع الرقمي |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | يضيف جزء نص رمزي في وضع النص |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | يضيف جزء نص رمزي في وضع Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | يضيف جزء نص رمزي في وضع URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | يعيد النص الرمزي من مُنشئ نص رمزي للوضع الموسع |

## أمثلة

```csharp
[C#]
//وضع النص الشيفري الموسع.
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

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//توليد نص شيفرة.
var str = codeTextBuilder.GetExtendedCodetext();

//توليد.
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

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


