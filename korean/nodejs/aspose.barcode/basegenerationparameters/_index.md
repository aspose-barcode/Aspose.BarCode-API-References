---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "바코드 이미지 생성 매개변수."
type: docs
weight: 160
url: /ko/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

바코드 이미지 생성 매개변수.

```js
new BaseGenerationParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | 바코드 이미지의 배경 색상. 기본값: #FFFFFF |
| [getBarcode()](#getbarcode) | 모든 바코드 속성을 포함하는 BarcodeParameters를 가져옵니다. |
| [getBorder()](#getborder) | 바코드 테두리의 모든 구성 속성을 포함하는 BorderParameters를 가져옵니다. |
| [getCaptionAbove()](#getcaptionabove) | BarCode 이미지 위의 캡션. CaptionParameters를 참조하십시오. |
| [getCaptionBelow()](#getcaptionbelow) | BarCode 이미지 아래의 캡션. CaptionParameters를 참조하십시오. |
| [getImage()](#getimage) | 이미지 매개변수. ImageParameters를 참조하십시오. |
| [getImageHeight()](#getimageheight) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이. |
| [getImageWidth()](#getimagewidth) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비. |
| [getResolution()](#getresolution) | BarCode 이미지의 해상도를 가져옵니다. 두 차원 모두에 적용되는 하나의 값입니다. 기본값: 96 dpi. Resolution 매개변수 |
| [getRotationAngle()](#getrotationangle) | BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. If Ro |
| [getUseAntiAlias()](#getuseantialias) | 이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져옵니다. |
| [setAutoSizeMode()](#setautosizemode) | 자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | 바코드 이미지의 배경 색상. 기본값: #FFFFFF |
| [setImageHeight()](#setimageheight) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이. |
| [setImageWidth()](#setimagewidth) | AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비. |
| [setResolution()](#setresolution) | BarCode 이미지의 해상도를 설정합니다. 두 차원 모두에 적용되는 하나의 값입니다. 기본값: 96 dpi. Resolution 매개변수 |
| [setRotationAngle()](#setrotationangle) | BarCode 이미지 회전 각도(도 단위), 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. If Ro |
| [setUseAntiAlias()](#setuseantialias) | 이미지를 렌더링할 때 안티앨리어싱 모드를 사용할지 여부를 나타내는 값을 설정합니다. |

### getAutoSizeMode() {#getautosizemode}

자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

바코드 이미지의 배경 색상. 기본값: #FFFFFF

### getBarcode() {#getbarcode}

모든 바코드 속성을 포함하는 BarcodeParameters를 가져옵니다.

### getBorder() {#getborder}

바코드 테두리의 모든 구성 속성을 포함하는 BorderParameters를 가져옵니다.

### getCaptionAbove() {#getcaptionabove}

BarCode 이미지 위의 캡션. CaptionParameters를 참조하십시오.

### getCaptionBelow() {#getcaptionbelow}

BarCode 이미지 아래의 캡션. CaptionParameters를 참조하십시오.

### getImage() {#getimage}

이미지 매개변수. ImageParameters를 참조하십시오.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이.

### getImageWidth() {#getimagewidth}

AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비.

### getResolution() {#getresolution}

바코드 이미지의 해상도를 가져옵니다. 두 차원 모두에 대해 하나의 값이 사용됩니다. 기본값: 96 dpi. 해상도 매개변수 값이 0 이하인 경우.

### getRotationAngle() {#getrotationangle}

바코드 이미지 회전 각도(도 단위). 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

이미지를 렌더링할 때 안티앨리어싱 모드가 사용되는지 여부를 나타내는 값을 가져옵니다.

### setAutoSizeMode() {#setautosizemode}

자동 크기 조정 모드의 다양한 유형을 지정합니다. 기본값: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

바코드 이미지의 배경 색상. 기본값: #FFFFFF

### setImageHeight() {#setimageheight}

AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 높이.

### setImageWidth() {#setimagewidth}

AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 BarCode 이미지 너비.

### setResolution() {#setresolution}

바코드 이미지의 해상도를 설정합니다. 두 차원 모두에 대해 하나의 값이 사용됩니다. 기본값: 96 dpi. 해상도 매개변수 값이 0 이하인 경우.

### setRotationAngle() {#setrotationangle}

바코드 이미지 회전 각도(도 단위). 예: RotationAngle = 0 또는 RotationAngle = 360은 회전이 없음을 의미합니다. RotationAngle가 90, 180, 270 또는 0이 아니면 스캐너가 이미지를 읽기 어려워질 수 있습니다. 기본값: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

이미지를 렌더링할 때 안티앨리어싱 모드를 사용할지 여부를 나타내는 값을 설정합니다.
