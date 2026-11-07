---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder 클래스"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::DotCodeExtCodetextBuilder 클래스를 사용하는 방법."
type: docs
weight: 2100
url: /ko/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | 확장 코드텍스트 항목에 FNC1 형식 식별자를 추가합니다. |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | 확장 코드텍스트 항목에 FNC3 리더 초기화를 추가합니다. |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | 확장 코드텍스트 항목에 FNC3 심볼 구분자를 추가합니다. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 확장 코드텍스트 항목에 일반 코드텍스트를 추가합니다. |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | 확장 코드텍스트 항목에 구조화된 추가 모드를 추가합니다. |
| virtual [Clear](../extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |
## 비고


DotCodeEncodeMode의 ExtendedCodetext 모드용 2D DotCode 바코드에 대한 확장 코드텍스트 생성기


```cpp
[C#]
//확장 코드텍스트 모드
//코드텍스트 생성
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//코드텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 또 보기

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
