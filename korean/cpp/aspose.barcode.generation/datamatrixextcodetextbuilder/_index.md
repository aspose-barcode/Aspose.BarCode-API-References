---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder 클래스"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder 클래스를 사용하는 방법."
type: docs
weight: 1900
url: /ko/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | 정의된 인코드 모드와 함께 코드 텍스트를 확장된 코드 텍스트 항목에 추가합니다. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | 정의된 인코드 모드와 함께 확장 채널 식별자를 사용하여 코드 텍스트를 추가합니다. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 확장 코드텍스트 항목에 일반 코드텍스트를 추가합니다. |
| virtual [Clear](../extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |
## 비고


EncodeMode의 ExtendedCodetext 모드에 대한 2D DataMatrix 바코드용 확장 코드 텍스트 생성기.


```cpp
[C#]
//확장 코드텍스트 모드

//코드텍스트 생성
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//코드텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 또 보기

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
