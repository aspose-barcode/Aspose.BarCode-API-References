---
title: "클래스 Unit"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.Unit 클래스. 픽셀, 인치 등 다양한 단위의 크기 값을 지정합니다."
type: docs
weight: 1740
url: /ko/net/aspose.barcode.generation/unit/
---
## Unit class

다양한 단위(픽셀, 인치 등)로 크기 값을 지정합니다.

```csharp
public sealed class Unit
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | 문서 단위의 크기 값을 가져오거나 설정합니다. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | 인치 단위의 크기 값을 가져오거나 설정합니다. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | 밀리미터 단위의 크기 값을 가져오거나 설정합니다. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | 픽셀 단위의 크기 값을 가져오거나 설정합니다. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | 포인트 단위의 크기 값을 가져오거나 설정합니다. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | 해상도 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | 이 인스턴스와 지정된 객체(또한 `Unit` 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | 이 객체의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | 이 `Unit`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

## 예제

이 샘플은 BarCode 이미지를 생성하고 저장하는 방법을 보여줍니다.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


