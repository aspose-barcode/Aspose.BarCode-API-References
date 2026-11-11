---
title: "클래스 DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder 클래스. EncodeMode의 ExtendedCodetext 모드용 2D DataMatrix 바코드에 대한 확장 코드텍스트 생성기"
type: docs
weight: 1210
url: /ko/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

EncodeMode의 ExtendedCodetext Mode용 2D DataMatrix 바코드용 확장 코드텍스트 생성기

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | 정의된 인코드 모드와 함께 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | 정의된 인코드 모드와 함께 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | 일반 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | 확장 코드텍스트 항목을 지웁니다. |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

## 예제

```csharp
[C#]
//Extended codetext 모드

//코덱텍스트 생성
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//코덱텍스트 생성
string codetext = textBuilder.GetExtendedCodetext();    

//생성
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### 또 보기

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


