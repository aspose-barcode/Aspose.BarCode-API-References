---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다."
type: docs
weight: 860
url: /ko/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다. |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다. |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다. |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [getBarcodeQuality()](#getbarcodequality) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소 r |
| [getComplexBackground()](#getcomplexbackground) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getDeconvolution()](#getdeconvolution) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 함수입니다. |
| [getInverseImage()](#getinverseimage) | 역색(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [getMinimalXDimension()](#getminimalxdimension) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀). |
| [getXDimension()](#getxdimension) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | 엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 손상된 바코드를 인식하는 데 사용할 수 있습니다. |
| [setBarcodeQuality(value)](#setbarcodequality) | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소 r |
| [setComplexBackground(value)](#setcomplexbackground) | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setDeconvolution(value)](#setdeconvolution) | 이미지 복원(Deconvolution) 모드로, 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 함수입니다. |
| [setInverseImage(value)](#setinverseimage) | 역색(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드. |
| [setMinimalXDimension(value)](#setminimalxdimension) | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀). |
| [setXDimension(value)](#setxdimension) | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드. |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다. 이 예제는 MaxQuality 모드를 사용하는 방법을 보여줍니다. reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } 값: MaxQuality 인식 품질 프리셋.

### getNormalQuality() (static) {#getnormalquality}

NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요해 인식 속도가 느려집니다.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Deconvolution(이미지 복원) 모드는 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 카메라로 이미지를 얻는 과정에서 흐림과 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 일반적으로 알려진 sharp나 수학적 형태학과 같은 함수를 확인해야 합니다.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

역색(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

엔진이 체크섬이 잘못되었거나 값이 올바르지 않은 바코드를 인식하도록 허용합니다. 이 모드는 텍스트가 잘못된 손상된 바코드를 인식하는 데 사용할 수 있습니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 엔진이 잘못된 바코드를 인식하도록 허용합니다. |

### setBarcodeQuality(value) {#setbarcodequality}

선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요해 인식 속도가 느려집니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드. |

### setComplexBackground(value) {#setcomplexbackground}

컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 컬러 이미지에서 컬러 바코드의 추가 인식. |

### setDeconvolution(value) {#setdeconvolution}

Deconvolution(이미지 복원) 모드는 이미지 손상 수준을 정의합니다. 원래 Deconvolution은 카메라로 이미지를 얻는 과정에서 흐림과 같은 자연 함수에 의해 손상(컨볼루션)된 이미지를 복원할 수 있는 기능입니다. 이미지 손상을 일으키는 함수를 감지할 수 없기 때문에, 우리는 일반적으로 알려진 sharp나 수학적 형태학과 같은 함수를 확인해야 합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 이미지 손상 수준을 정의하는 Deconvolution 모드. |

### setInverseImage(value) {#setinverseimage}

역색(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 역색 이미지에서 바코드의 추가 인식 |

### setMinimalXDimension(value) {#setminimalxdimension}

UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀).

| 매개변수 | 설명 |
| --- | --- |
| 값 | UseMinimalXDimension과 함께 사용되는 XDimension의 최소 크기(픽셀). |

### setXDimension(value) {#setxdimension}

바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지)를 설정하는 인식 모드.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 바코드 최소 요소(매트릭스 셀 또는 바)의 크기(1부터 무한대까지). |
