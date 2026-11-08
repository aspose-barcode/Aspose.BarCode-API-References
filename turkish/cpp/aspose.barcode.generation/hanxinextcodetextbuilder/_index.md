---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder sınıfı"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'ta Aspose::BarCode::Generation::HanXinExtCodetextBuilder sınıfını nasıl kullanılır."
type: docs
weight: 2800
url: /tr/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Auto modunda kod metni parçacığını ekler |
| [AddBinary](./addbinary/)(System::String) | Binary modunda kod metni parçacığını ekler |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region One modunda kod metni parçacığını ekler |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region Two modunda kod metni parçacığını ekler |
| [AddECI](./addeci/)(System::String, int32_t) | ECI modunda kod metni parçacığını ekler |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | GB18030 Four Byte modunda kod metni parçacığını ekler |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | GB18030 Two Byte modunda kod metni parçacığını ekler |
| [AddNumeric](./addnumeric/)(System::String) | Numeric modunda kod metni parçacığını ekler |
| [AddText](./addtext/)(System::String) | Text modunda kod metni parçacığını ekler |
| [AddUnicode](./addunicode/)(System::String) | Unicode modunda kod metni parçacığını ekler |
| [AddURI](./adduri/)(System::String) | URI modunda kod metni parçacığını ekler |
| [GetExtendedCodetext](./getextendedcodetext/)() | Extended mode kod metni oluşturucusundan kod metnini döndürür |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Açıklamalar


EncodeMode'un Extended Mode'u için Han Xin Code'a ait genişletilmiş kod metni oluşturucu


```cpp
[C#]
//Genişletilmiş kod metni modu
//kod metni oluştur
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

//kod metni üret
var str = codeTextBuilder.GetExtendedCodetext();

//üret
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
