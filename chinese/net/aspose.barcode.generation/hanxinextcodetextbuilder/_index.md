---
title: "类 HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder 类。用于 Han Xin Code 扩展模式的扩展码文本生成器"
type: docs
weight: 1380
url: /zh/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

用于 EncodeMode 的扩展模式的 Han Xin Code 的扩展代码文本生成器

```csharp
public class HanXinExtCodetextBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | 在自动模式下添加码文本片段 |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | 在二进制模式下添加码文本片段 |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | 在通用中文区域一模式下添加码文本片段 |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | 在通用中文区域二模式下添加码文本片段 |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | 在 ECI 模式下添加码文本片段 |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | 在 GB18030 四字节模式下添加码文本片段 |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | 在 GB18030 双字节模式下添加码文本片段 |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | 在数字模式下添加码文本片段 |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | 在 Text 模式中添加代码文本片段 |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | 在 Unicode 模式中添加代码文本片段 |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | 在 URI 模式中添加代码文本片段 |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | 从 Extended 模式的代码文本构建器返回代码文本 |

## 示例

```csharp
[C#]
//Extended codetext 模式
//创建代码文本
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

//生成代码文本
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

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


