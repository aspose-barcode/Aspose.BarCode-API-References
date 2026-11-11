---
title: "Quadrangle 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.Quadrangle 클래스. 사각형 영역을 나타내는 네 개의 Point 집합을 저장합니다."
type: docs
weight: 360
url: /ko/net/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class

네 개의 Point 집합을 저장하며, 이는 `Quadrangle` 영역을 나타냅니다.

```csharp
public class Quadrangle : IEquatable<Quadrangle>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Quadrangle](quadrangle/#constructor)() | `Quadrangle` 클래스의 새로운 빈 인스턴스를 초기화합니다. |
| [Quadrangle](quadrangle/#constructor_1)(Point, Point, Point, Point) | `Quadrangle` 클래스의 새로운 인스턴스를 설명 포인트와 함께 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BoundingRectangle](../../aspose.barcode.barcoderecognition/quadrangle/boundingrectangle/) { get; } | 이 `Quadrangle`을 둘러싸는 Rectangle을 가져옵니다. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/quadrangle/isempty/) { get; } | 이 `Quadrangle`의 모든 Point가 값이 0인지 테스트합니다. |
| [LeftBottom](../../aspose.barcode.barcoderecognition/quadrangle/leftbottom/) { get; set; } | `Quadrangle` 영역의 왼쪽 하단 코너 Point를 가져옵니다. |
| [LeftTop](../../aspose.barcode.barcoderecognition/quadrangle/lefttop/) { get; set; } | `Quadrangle` 영역의 왼쪽 상단 코너 Point를 가져옵니다. |
| [RightBottom](../../aspose.barcode.barcoderecognition/quadrangle/rightbottom/) { get; set; } | `Quadrangle` 영역의 오른쪽 하단 코너 Point를 가져옵니다. |
| [RightTop](../../aspose.barcode.barcoderecognition/quadrangle/righttop/) { get; set; } | `Quadrangle` 영역의 오른쪽 상단 코너 Point를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_2)(Point) | 지정된 Point가 이 `Quadrangle` 클래스에 포함되는지 여부를 결정합니다. |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains)(Quadrangle) | 지정된 `Quadrangle`이 이 `Quadrangle` 클래스에 포함되거나 교차하는지 여부를 결정합니다. |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_3)(Rectangle) | 지정된 Rectangle이 이 `Quadrangle` 클래스에 포함되거나 교차하는지 여부를 결정합니다. |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_1)(int, int) | 지정된 point가 이 `Quadrangle` 클래스에 포함되는지 여부를 결정합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/quadrangle/equals/#equals_1)(object) | 이 인스턴스가 지정된 `Quadrangle` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [Equals](../../aspose.barcode.barcoderecognition/quadrangle/equals/#equals)(Quadrangle) | 이 인스턴스가 지정된 `Quadrangle` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/quadrangle/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/quadrangle/tostring/)() | 이 `Quadrangle`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/quadrangle/op_equality/) | 첫 번째 `Quadrangle` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/quadrangle/op_inequality/) | 첫 번째 `Quadrangle` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Empty](../../aspose.barcode.barcoderecognition/quadrangle/empty/) | `Quadrangle` 클래스를 나타내며, 해당 속성들은 초기화되지 않은 상태입니다. |

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


