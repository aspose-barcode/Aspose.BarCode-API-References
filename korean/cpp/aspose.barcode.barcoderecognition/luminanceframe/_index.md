---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame 클래스"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame 클래스. 8비트 그레이스케일 이미지 프레임을 나타냅니다. 각 픽셀은 C++에서 그 밝기 값을 포함하는 1바이트로 표현됩니다."
type: docs
weight: 2400
url: /ko/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


8비트 그레이스케일 이미지 프레임을 나타냅니다. 각 픽셀은 밝기 값을 포함하는 1바이트로 표현됩니다.

```cpp
class LuminanceFrame : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Data](./get_data/)() const | 밝기 데이터를 가져옵니다. |
| [get_Height](./get_height/)() const | 프레임 높이를 픽셀 단위로 가져옵니다. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | 프레임을 올바른 방향으로 만들기 위해 시계 방향으로 회전해야 하는 각도를 가져옵니다. |
| [get_RowStride](./get_rowstride/)() const | 두 인접 행의 시작점 사이의 바이트 거리를 가져옵니다. |
| [get_Width](./get_width/)() const | 프레임 너비를 픽셀 단위로 가져옵니다. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | 패딩 없이 행 사이에 새로운 [LuminanceFrame](./) 클래스 인스턴스를 초기화합니다. 인접 행 사이의 거리는 *width* 와 같습니다. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | 지정된 행 스트라이드로 새로운 [LuminanceFrame](./) 클래스 인스턴스를 초기화합니다. |
## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
