---
title: QrExtCodetextBuilder
second_title: .NET API 참조용 Aspose.BarCode
description: QrEncodeMode의 ExtendedCodetext 모드용 2D QR 바코드용 확장 코드텍스트 생성기
type: docs
weight: 1190
url: /ko/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

QrEncodeMode의 ExtendedCodetext 모드용 2D QR 바코드용 확장 코드텍스트 생성기

BarcodeGenerator의 TwoDDisplayText 속성을 사용하여 관리 문자를 제거하기 위해 보이는 텍스트를 설정합니다.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | 기본 생성자입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 확장 채널 식별자 로 코드 텍스트를 추가합니다. |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | 확장 코드 텍스트 items 의 첫 번째 위치에 FNC1을 추가합니다. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | 확장 코드 텍스트 items 에 그룹 구분 기호(GS - '\\u001D')를 추가합니다. |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | 확장된 코드 텍스트 items 에 두 번째 위치에 FNC1을 추가합니다. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 확장된 코드 텍스트 items 에 일반 코드 텍스트를 추가합니다. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 확장 코드 텍스트를 지웁니다. items |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### 예

이 샘플은 확장 모드에서 FNC1 첫 번째 위치를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
lTextBuilder.AddFNC1FirstPosition();
lTextBuilder.AddPlainCodetext("000%89%%0");
lTextBuilder.AddFNC1GroupSeparator();
lTextBuilder.AddPlainCodetext("12345<FNC1>");

//코드 텍스트 생성
string lCodetext = lTextBuilder.GetExtendedCodetext();

//생성하다
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

이 샘플은 확장 모드에서 FNC1 두 번째 위치를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//코드 텍스트 생성
string lCodetext = lTextBuilder.GetExtendedCodetext();

//생성하다
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

이 샘플은 확장 모드에서 다중 ECI 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
//코드텍스트 생성
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");   

//코드 텍스트 생성
string lCodetext = lTextBuilder.GetExtendedCodetext();

//생성하다
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### 또한보십시오

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* 네임스페이스 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
