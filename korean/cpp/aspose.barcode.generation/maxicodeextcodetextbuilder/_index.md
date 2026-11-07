---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder class"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder 클래스를 사용하는 방법."
type: docs
weight: 3500
url: /ko/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 확장 코드텍스트 항목에 일반 코드텍스트를 추가합니다. |
| virtual [Clear](../extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |
## 비고


MaxiCodeEncodeMode의 ExtendedCodetext 모드용 MaxiCode 바코드 확장 코드텍스트 생성기

[BarcodeGenerator](../barcodegenerator/)의 TwoDDisplayText 속성을 사용하여 표시 텍스트를 관리 문자를 제거하도록 설정합니다.

이 샘플은 확장 모드에서 [MaxiCodeExtCodetextBuilder](./)를 사용하는 방법을 보여줍니다.
```cpp
[C#]
//코드텍스트 생성
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//코드텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 또 보기

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
