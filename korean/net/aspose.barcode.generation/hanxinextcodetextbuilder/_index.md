---
title: "Class HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder 클래스. EncodeMode의 확장 모드용 한신 코드에 대한 확장 코드텍스트 생성기"
type: docs
weight: 1380
url: /ko/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

EncodeMode의 Extended Mode용 Han Xin Code용 확장 코드텍스트 생성기

```csharp
public class HanXinExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | 자동 모드에서 코드텍스트 조각을 추가합니다 |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | 이진 모드에서 코드텍스트 조각을 추가합니다 |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | 공통 중국 지역 1 모드에서 코드텍스트 조각을 추가합니다 |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | 공통 중국 지역 2 모드에서 코드텍스트 조각을 추가합니다 |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | ECI 모드에서 코드텍스트 조각을 추가합니다 |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | GB18030 4바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | GB18030 2바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | 숫자 모드에서 코드텍스트 조각을 추가합니다 |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | 텍스트 모드에서 코드 텍스트 조각을 추가합니다 |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | 유니코드 모드에서 코드 텍스트 조각을 추가합니다 |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | URI 모드에서 코드 텍스트 조각을 추가합니다 |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Extended 모드 코드 텍스트 빌더에서 코드 텍스트를 반환합니다 |

## 예제

```csharp
[C#]
//Extended codetext 모드
//코덱텍스트 생성
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

//코덱텍스트 생성
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

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


