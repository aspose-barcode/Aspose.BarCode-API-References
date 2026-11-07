---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder 클래스"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::HanXinExtCodetextBuilder 클래스를 사용하는 방법."
type: docs
weight: 2800
url: /ko/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Auto 모드에서 코드텍스트 조각을 추가합니다 |
| [AddBinary](./addbinary/)(System::String) | Binary 모드에서 코드텍스트 조각을 추가합니다 |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region One 모드에서 코드텍스트 조각을 추가합니다 |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region Two 모드에서 코드텍스트 조각을 추가합니다 |
| [AddECI](./addeci/)(System::String, int32_t) | ECI 모드에서 코드텍스트 조각을 추가합니다 |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | GB18030 Four Byte 모드에서 코드텍스트 조각을 추가합니다 |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | GB18030 Two Byte 모드에서 코드텍스트 조각을 추가합니다 |
| [AddNumeric](./addnumeric/)(System::String) | Numeric 모드에서 코드텍스트 조각을 추가합니다 |
| [AddText](./addtext/)(System::String) | Text 모드에서 코드텍스트 조각을 추가합니다 |
| [AddUnicode](./addunicode/)(System::String) | Unicode 모드에서 코드텍스트 조각을 추가합니다 |
| [AddURI](./adduri/)(System::String) | URI 모드에서 코드텍스트 조각을 추가합니다 |
| [GetExtendedCodetext](./getextendedcodetext/)() | Extended 모드 코드텍스트 빌더에서 코드텍스트를 반환합니다 |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## 비고


EncodeMode의 Extended Mode용 Han Xin Code에 대한 확장 코드텍스트 생성기


```cpp
[C#]
//확장 코드텍스트 모드
//코드텍스트 생성
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

//코드텍스트 생성
var str = codeTextBuilder.GetExtendedCodetext();

//생성
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

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
