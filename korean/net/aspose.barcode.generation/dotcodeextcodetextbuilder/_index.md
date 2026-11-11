---
title: "클래스 DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder 클래스. 2D DotCode 바코드의 ExtendedCodetext 모드인 DotCodeEncodeMode를 위한 확장 코드텍스트 생성기"
type: docs
weight: 1250
url: /ko/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

DotCodeEncodeMode의 ExtendedCodetext Mode용 2D DotCode 바코드용 확장 코드텍스트 생성기

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | 확장 코드텍스트 항목에 FNC1 형식 식별자를 추가합니다. |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | 확장 코드텍스트 항목에 FNC3 리더 초기화를 추가합니다. |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | 확장 코드텍스트 항목에 FNC3 심볼 구분자를 추가합니다. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 일반 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | 확장 코드텍스트 항목에 구조적 추가 모드를 추가합니다. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

## 예제

```csharp
[C#]
//Extended codetext 모드
//코덱텍스트 생성
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

//코덱텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();    

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### 또 보기

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


