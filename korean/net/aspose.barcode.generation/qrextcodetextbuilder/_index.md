---
title: "클래스 QrExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder 클래스. ExtendedCodetext 모드의 EncodeMode에 대한 2D QR 바코드용 확장 코드텍스트 생성기"
type: docs
weight: 1630
url: /ko/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

EncodeMode의 ExtendedCodetext Mode용 2D QR 바코드용 확장 코드텍스트 생성기

BarcodeGenerator의 TwoDDisplayText 속성을 사용하여 표시 텍스트를 설정하고 관리 문자를 제거합니다.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | 지정된 QR 압축 모드와 함께 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | 첫 번째 위치에 FNC1을 설정합니다. 이전에 다른 FNC1 모드가 설정되어 있었다면 교체됩니다. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | 그룹 구분자(GS - "\\u001D")를 확장 코드텍스트 항목에 추가합니다 |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | 두 번째 위치에 FNC1을 설정합니다. 이전에 다른 FNC1 모드가 설정되어 있었다면 교체됩니다. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 일반 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

## 예제

이 샘플은 확장 모드에서 FNC1 첫 번째 위치를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//코덱텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//코덱텍스트 생성
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

```csharp
[C#]
//코덱텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//코덱텍스트 생성
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

```csharp
[C#]
//코덱텍스트 생성
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//코덱텍스트 생성
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

### 또 보기

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


