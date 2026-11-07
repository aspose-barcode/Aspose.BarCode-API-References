---
title: "생성자"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 생성자. C++에서 행 사이에 패딩 없이 LuminanceFrame 클래스의 새 인스턴스를 초기화합니다. 인접한 행 사이의 거리는 width와 같습니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


행 사이에 패딩 없이 [LuminanceFrame](../) 클래스의 새 인스턴스를 초기화합니다. 인접한 행 사이의 거리는 *width*와 같습니다.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 픽셀당 1바이트를 포함하는 밝기 데이터. |
| width | int32_t | 프레임의 너비(픽셀 단위). |
| height | int32_t | 프레임의 높이(픽셀 단위). |
| rotationDegrees | int32_t | 프레임을 정상적으로 표시하기 위해 필요한 시계 방향 회전입니다. 지원되는 값은 0, 90, 180, 270이며 기본값은 0입니다. |

## 또 보기

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


지정된 row stride를 사용하여 [LuminanceFrame](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 픽셀당 1바이트를 포함하는 밝기 데이터. |
| width | int32_t | 프레임의 너비(픽셀 단위). |
| height | int32_t | 프레임의 높이(픽셀 단위). |
| rowStride | int32_t | 두 인접 행의 시작 사이의 바이트 단위 거리입니다. 값은 *width* 보다 작을 수 없습니다. |
| rotationDegrees | int32_t | 프레임을 바로 세우기 위해 필요한 시계 방향 회전입니다. 지원되는 값은 0, 90, 180 및 270입니다. |

## 또 보기

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
