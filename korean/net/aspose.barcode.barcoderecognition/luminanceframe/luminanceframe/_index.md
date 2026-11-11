---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode for .NET API 참조"
description: "LuminanceFrame 생성자. 행 사이에 패딩 없이 LuminanceFrame 클래스의 새 인스턴스를 초기화합니다. 인접한 행 사이의 거리는 width와 같습니다"
type: docs
weight: 10
url: /ko/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

행 사이에 패딩 없이 [`LuminanceFrame`](../) 클래스의 새 인스턴스를 초기화합니다. 인접한 행 사이의 거리는 *width*와 같습니다.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | Byte[] | 픽셀당 한 바이트를 포함하는 휘도 데이터입니다. |
| width | Int32 | 프레임의 너비(픽셀 단위)입니다. |
| height | Int32 | 프레임의 높이(픽셀 단위)입니다. |
| rotationDegrees | Int32 | 프레임을 올바르게 표시하기 위해 필요한 시계 방향 회전입니다. 지원되는 값은 0, 90, 180 및 270이며, 기본값은 0입니다. |

### 또 보기

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

지정된 row stride로 [`LuminanceFrame`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | Byte[] | 픽셀당 한 바이트를 포함하는 휘도 데이터입니다. |
| width | Int32 | 프레임의 너비(픽셀 단위)입니다. |
| height | Int32 | 프레임의 높이(픽셀 단위)입니다. |
| rowStride | Int32 | 두 인접 행의 시작 사이의 바이트 거리입니다. 값은 *width*보다 작을 수 없습니다. |
| rotationDegrees | Int32 | 프레임을 올바르게 표시하기 위해 필요한 시계 방향 회전입니다. 지원되는 값은 0, 90, 180 및 270입니다. |

### 또 보기

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


