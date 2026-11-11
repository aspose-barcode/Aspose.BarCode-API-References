---
title: "SymbologyEncodeType 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.SymbologyEncodeType 클래스. 심볼 인코드 유형. 인스턴스를 얻으려면 EncodeTypes를 참조하십시오."
type: docs
weight: 1710
url: /ko/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

심볼로지 인코드 유형. 인스턴스를 얻으려면 EncodeTypes를 참조하십시오.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | 이 심볼의 분류를 가져옵니다. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | 인코드 유형의 인덱스를 가져옵니다. |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | 인코드 유형의 이름을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | 이 인스턴스가 지정된 [`BaseEncodeType`](../baseencodetype/) 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | 이 인스턴스가 지정된 [`BaseEncodeType`](../baseencodetype/) 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | BaseEncodeType 인스턴스를 동등한 문자열 표현으로 변환합니다. 문자열 형식은: "Index:0; Name:Codabar" 입니다. |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | 주어진 BaseEncodeType의 이름을 문자열로 반환합니다. |

## 예제

이 샘플은 SymbologyEncodeType 클래스의 인스턴스를 가져오는 방법을 보여줍니다.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### 또 보기

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


