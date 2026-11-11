---
title: "클래스 BaseDecodeType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType 클래스. MultiDecodeType 및 SingleDecodeType의 기본 클래스"
type: docs
weight: 130
url: /ko/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

MultiDecodeType 및 SingleDecodeType의 기본 클래스.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | 주어진 디코드 유형 중 하나가 포함되어 있는지 여부를 결정합니다 |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | `BaseDecodeType` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | [`MultiDecodeType`](../multidecodetype/) 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | `BaseDecodeType` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | [`SingleDecodeType`](../singledecodetype/) 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | BaseDecodeType의 문자열 표현을 해당 인스턴스로 변환하며, 구체적인 유형을 결정합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |

## 예제

이 샘플은 BaseDecodeType을 SingleDecodeType 및 MultiDecodeType과 함께 사용하는 방법을 보여줍니다.

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


