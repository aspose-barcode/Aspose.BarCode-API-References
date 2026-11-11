---
title: "클래스 AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder 클래스. AztecEncodeMode의 ExtendedCodetext 모드용 Aztec 바코드에 대한 확장 코드텍스트 생성기"
type: docs
weight: 950
url: /ko/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

AztecEncodeMode의 ExtendedCodetext 모드용 Aztec 바코드에 대한 확장 코드텍스트 생성기

BarcodeGenerator의 TwoDDisplayText 속성을 사용하여 표시 텍스트를 설정하고 관리 문자를 제거합니다.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 일반 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

## 예제

이 샘플은 확장 모드에서 AztecExtCodetextBuilder를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//코덱텍스트 생성
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//코덱텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();    

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 또 보기

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


