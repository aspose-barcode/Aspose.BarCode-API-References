---
title: "클래스 SingleDecodeType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType 클래스. 단일 디코드 유형입니다. 인스턴스를 얻으려면 디코드 유형을 참조하십시오."
type: docs
weight: 390
url: /ko/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

단일 디코드 유형입니다. 인스턴스를 얻으려면 decode type을 참조하십시오.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | 디코드 유형의 인덱스를 가져옵니다. |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | 디코드 유형의 이름을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | SingleDecodeType 이름의 문자열 표현을 해당 인스턴스로 변환합니다. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | 이 인스턴스가 지정된 목록에 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | 이 인스턴스가 지정된 [`BaseDecodeType`](../basedecodetype/) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | 지정된 [`MultiDecodeType`](../multidecodetype/) 컬렉션에 이 디코드 유형만 포함되어 있는지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | 이 인스턴스가 지정된 `SingleDecodeType` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | 이 인스턴스가 지정된 `SingleDecodeType` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | SingleDecodeType 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | 주어진 SingleDecodeType의 이름을 문자열로 반환합니다. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | SingleDecodeType 인스턴스를 해당 문자열 표현으로 변환합니다. 문자열 형식은: "Index:-1; Name:None". |

## 예제

이 샘플은 단일 디코드 유형의 인스턴스를 가져오는 방법을 보여줍니다.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### 또 보기

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


