---
title: "클래스 MultiDecodeType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType 클래스. 복합 디코드 유형"
type: docs
weight: 320
url: /ko/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

복합 디코드 유형입니다.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | `MultiDecodeType` 클래스의 새 인스턴스를 초기화합니다. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | `MultiDecodeType` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | 단일 유형의 수를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | MultiDecodeType에 하나의 추가 [`SingleDecodeType`](../singledecodetype/)를 추가합니다. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | 이 객체가 바코드 유형의 모든 유형을 포함하는지 확인합니다. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | 어떤 유형이라도 포함하고 있는지 확인합니다. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | 이 인스턴스가 지정된 [`BaseDecodeType`](../basedecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | 이 인스턴스가 지정된 `MultiDecodeType` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | 이 인스턴스가 지정된 `MultiDecodeType` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | 이 디코드 유형 컬렉션이 지정된 [`SingleDecodeType`](../singledecodetype/) 값만 포함하는지 여부를 나타내는 값을 반환합니다. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | `MultiDecodeType`에서 [`SingleDecodeType`](../singledecodetype/)을 제외하고 새로운 MultiDecodeType 인스턴스를 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | 단일 유형 목록을 나타냅니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | MultiDecodeType을 문자열로 나타내는 재정의된 메서드입니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |

## 예제

이 샘플은 SingleDecodeType과 MultiDecode 유형을 결합한 복합 MultiDecode 유형을 만드는 방법을 보여줍니다.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### 또 보기

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


