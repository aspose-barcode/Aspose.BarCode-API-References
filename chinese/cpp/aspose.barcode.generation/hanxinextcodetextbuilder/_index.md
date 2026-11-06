---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder 类"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::Generation::HanXinExtCodetextBuilder 类。"
type: docs
weight: 2800
url: /zh/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | 在 Auto 模式下添加编码文本片段 |
| [AddBinary](./addbinary/)(System::String) | 在 Binary 模式下添加编码文本片段 |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | 在 [Common](../../aspose.barcode.common/) 中文地区一 模式下添加编码文本片段 |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | 在 [Common](../../aspose.barcode.common/) 中文地区二 模式下添加编码文本片段 |
| [AddECI](./addeci/)(System::String, int32_t) | 在 ECI 模式下添加编码文本片段 |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | 在 GB18030 四字节 模式下添加编码文本片段 |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | 在 GB18030 两字节 模式下添加编码文本片段 |
| [AddNumeric](./addnumeric/)(System::String) | 在 Numeric 模式下添加编码文本片段 |
| [AddText](./addtext/)(System::String) | 在 Text 模式下添加编码文本片段 |
| [AddUnicode](./addunicode/)(System::String) | 在 Unicode 模式下添加编码文本片段 |
| [AddURI](./adduri/)(System::String) | 在 URI 模式下添加编码文本片段 |
| [GetExtendedCodetext](./getextendedcodetext/)() | 从 Extended 模式的编码文本生成器返回编码文本 |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## 备注


用于 EncodeMode 的 Extended 模式下的汉信码扩展编码文本生成器


```cpp
[C#]
//扩展码文本模式
//创建码文本
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

//生成码文本
var str = codeTextBuilder.GetExtendedCodetext();

//生成
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

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
