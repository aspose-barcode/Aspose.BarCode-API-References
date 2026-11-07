---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "C++에서 Aspose::BarCode::Generation::QrExtCodetextBuilder 클래스를 사용하는 방법."
type: docs
weight: 4300
url: /ko/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | 지정된 QR 압축 모드와 함께 코드 텍스트를 확장된 코드 텍스트 항목에 추가합니다. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | 첫 번째 위치에 FNC1을 설정합니다. 이전에 다른 FNC1 모드가 설정되어 있었다면 교체됩니다. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | 확장 코드텍스트 항목에 그룹 구분자(GS - '\u001D')를 추가합니다. |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | 두 번째 위치에 FNC1을 설정합니다. 이전에 다른 FNC1 모드가 설정되어 있었다면 교체됩니다. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 확장 코드텍스트 항목에 일반 코드텍스트를 추가합니다. |
| [Clear](./clear/)() override | 확장 코드텍스트 항목을 지웁니다. |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## 비고


EncodeMode의 ExtendedCodetext 모드용 2D QR 바코드에 대한 확장 코드텍스트 생성기

[BarcodeGenerator](../barcodegenerator/)의 TwoDDisplayText 속성을 사용하여 표시 텍스트를 관리 문자를 제거하도록 설정합니다.

이 샘플은 확장 모드에서 FNC1 첫 번째 위치를 사용하는 방법을 보여줍니다.
```cpp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//코드텍스트 생성
string codetext = TextBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


이 샘플은 확장 모드에서 FNC1 두 번째 위치를 사용하는 방법을 보여줍니다.
```cpp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//코드텍스트 생성
string codetext = TextBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


이 샘플은 확장 모드에서 다중 ECI 모드를 사용하는 방법을 보여줍니다.
```cpp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//코드텍스트 생성
string codetext = TextBuilder.GetExtendedCodetext();

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 또 보기

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
