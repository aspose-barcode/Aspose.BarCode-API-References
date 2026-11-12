---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "바코드 생성 매개변수."
type: docs
weight: 140
url: /ko/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

바코드 생성 매개변수.

```js
new BarcodeParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost 바코드 매개변수. |
| [getAztec()](#getaztec) | Aztec 매개변수. |
| [getBarColor()](#getbarcolor) | 바 색상. |
| [getBarHeight()](#getbarheight) | 1D 바코드 바의 높이(단위 값). AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMo 로 설정된 경우 무시됩니다. |
| [getBarWidthReduction()](#getbarwidthreduction) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져옵니다. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [getCodabar()](#getcodabar) | Codabar 매개변수. |
| [getCodablock()](#getcodablock) | Codablock 매개변수. |
| [getCode16K()](#getcode16k) | Code16K 매개변수. |
| [getCode128()](#getcode128) | Code128 매개변수. |
| [getCodeTextParameters()](#getcodetextparameters) | 코드텍스트 매개변수. |
| [getCoupon()](#getcoupon) | 쿠폰 매개변수. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon에 사용됩니다. |
| [getDataBar()](#getdatabar) | Databar 매개변수. |
| [getDataMatrix()](#getdatamatrix) | DataMatrix 매개변수. |
| [getDotCode()](#getdotcode) | DotCode 매개변수. |
| [getEnableEscape()](#getenableescape) | CodeText 속성에서 문자 "\\"를 이스케이프 문자로 해석할지 여부를 나타냅니다. Pdf417, DataMatrix, C 에 사용됩니다. |
| [getFilledBars()](#getfilledbars) | 바가 채워졌는지 여부를 나타내는 값을 가져옵니다. 1D 바코드에만 적용됩니다. 기본값: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar 매개변수. 이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트에 유의하십시오 |
| [getHanXin()](#gethanxin) | HanXin 매개변수. |
| [getITF()](#getitf) | ITF 매개변수. |
| [getMaxiCode()](#getmaxicode) | MaxiCode 매개변수. |
| [getPadding()](#getpadding) | 바코드 패딩. 기본값: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | PatchCode 매개변수. |
| [getPdf417()](#getpdf417) | PDF417 매개변수. |
| [getPostal()](#getpostal) | 우편 매개변수. Postnet 및 Planet에 사용됩니다. |
| [getQR()](#getqr) | QR 매개변수. |
| [getSupplement()](#getsupplement) | 보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다. |
| [getWideNarrowRatio()](#getwidenarrowratio) | 넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF에 사용됩니다, |
| [getXDimension()](#getxdimension) | x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 i가 증가합니다 |
| [isChecksumEnabled()](#ischecksumenabled) | 1D 바코드 생성 시 체크섬을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼로는 Yes로 처리되며, N은 |
| [setBarColor(value)](#setbarcolor) | 바 색상. |
| [setBarHeight()](#setbarheight) | 1D 바코드 바의 높이(단위 값). AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMo 로 설정된 경우 무시됩니다. |
| [setBarWidthReduction()](#setbarwidthreduction) | 인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 설정합니다. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다. |
| [setChecksumEnabled()](#setchecksumenabled) | 1D 바코드 생성 시 체크섬을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼로는 Yes로 처리되며, N은 |
| [setEnableEscape()](#setenableescape) | CodeText 속성에서 문자 "\\"를 이스케이프 문자로 해석할지 여부를 나타냅니다. Pdf417, DataMatrix, C 에 사용됩니다. |
| [setFilledBars()](#setfilledbars) | 바가 채워졌는지 여부를 나타내는 값을 설정합니다. 1D 바코드에만 적용됩니다. 기본값: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar 매개변수. 이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트에 유의하십시오 |
| [setPadding()](#setpadding) | 바코드 패딩. 기본값: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | 넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, P에 사용됩니다 |
| [setXDimension()](#setxdimension) | x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 i가 증가합니다 |

### getAustralianPost() {#getaustralianpost}

AustralianPost 바코드 매개변수.

### getAztec() {#getaztec}

Aztec 매개변수.

### getBarColor() {#getbarcolor}

바 색상.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

1D 바코드 바의 높이(단위 값). AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 무시됩니다.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 가져옵니다.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다.

### getCodabar() {#getcodabar}

Codabar 매개변수.

### getCodablock() {#getcodablock}

Codablock 매개변수.

### getCode16K() {#getcode16k}

Code16K 매개변수.

### getCode128() {#getcode128}

Code128 매개변수.

### getCodeTextParameters() {#getcodetextparameters}

코드텍스트 매개변수.

### getCoupon() {#getcoupon}

쿠폰 매개변수. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon에 사용됩니다.

### getDataBar() {#getdatabar}

Databar 매개변수.

### getDataMatrix() {#getdatamatrix}

DataMatrix 매개변수.

### getDotCode() {#getdotcode}

DotCode 매개변수.

### getEnableEscape() {#getenableescape}

CodeText 속성에서 문자 "\\"를 이스케이프 문자로 해석할지 여부를 나타냅니다. Pdf417, DataMatrix, Code128에만 사용됩니다. EnableEscape가 true이면 "\\"는 특수 이스케이프 문자로 해석됩니다. 그렇지 않으면 "\\"는 일반 문자로 동작합니다. Aspose.BarCode는 ASCII 제어 코드 문자를 위한 10진수 ascii 코드와 니모닉 입력을 지원합니다. 예를 들어, \\013 및 \\\\CR은 CR을 나타냅니다.

### getFilledBars() {#getfilledbars}

바가 채워졌는지 여부를 나타내는 값을 가져옵니다. 1D 바코드에만 적용됩니다. 기본값: true.

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar 매개변수. 이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트는 '/' 기호로 구분됩니다.

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

HanXin 매개변수.

### getITF() {#getitf}

ITF 매개변수.

### getMaxiCode() {#getmaxicode}

MaxiCode 매개변수.

### getPadding() {#getpadding}

바코드 패딩. 기본값: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

PatchCode 매개변수.

### getPdf417() {#getpdf417}

PDF417 매개변수.

### getPostal() {#getpostal}

우편 매개변수. Postnet 및 Planet에 사용됩니다.

### getQR() {#getqr}

QR 매개변수.

### getSupplement() {#getsupplement}

보조 매개변수. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN에 사용됩니다.

### getWideNarrowRatio() {#getwidenarrowratio}

넓은 바와 좁은 바의 비율. 기본값: 3, 즉 넓은 바는 좁은 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard에 사용됩니다. WideNarrowRatio 매개변수 값이 0 이하인 경우.

### getXDimension() {#getxdimension}

x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 무시됩니다.

### isChecksumEnabled() {#ischecksumenabled}

1D 바코드 생성 시 체크섬을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼리지는 Yes로, 체크섬이 선택 가능한 경우는 No로 처리됩니다. 체크섬을 사용할 수 있는 심볼리지는: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. 체크섬이 항상 사용되는 심볼리지는 나머지 심볼리지입니다.

### setBarColor(value) {#setbarcolor}

바 색상.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | String | Bar 색상의 기본값: #000000. |

### setBarHeight() {#setbarheight}

1D 바코드 바의 높이(단위 값). AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 무시됩니다.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

인쇄 시 잉크 번짐을 보정하기 위해 사용되는 바 감소 값을 설정합니다.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Code128 및 GS1Code128 바코드에 대해 사람이 읽을 수 있는 텍스트에 체크섬 숫자를 항상 표시합니다.

### setChecksumEnabled() {#setchecksumenabled}

1D 바코드 생성 시 체크섬을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼리지는 Yes로, 체크섬이 선택 가능한 경우는 No로 처리됩니다. 체크섬을 사용할 수 있는 심볼리지는: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. 체크섬이 항상 사용되는 심볼리지는 나머지 심볼리지입니다.

### setEnableEscape() {#setenableescape}

CodeText 속성에서 "\\" 문자를 이스케이프 문자로 해석할지 여부를 나타냅니다. Pdf417, DataMatrix, Code128에만 사용됩니다. EnableEscape가 true이면 "\\"는 특수 이스케이프 문자로 해석됩니다. 그렇지 않으면 "\\"는 일반 문자로 동작합니다. Aspose.BarCode는 ASCII 제어 문자에 대한 10진수 ASCII 코드와 니모닉을 지원합니다. 예를 들어, \\013 및 \\\\CR은 CR을 나타냅니다.

### setFilledBars() {#setfilledbars}

바가 채워졌는지 여부를 나타내는 값을 설정합니다. 1D 바코드에만 적용됩니다. 기본값: true.

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar 매개변수. 이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트는 '/' 기호로 구분됩니다.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

바코드 패딩. 기본값: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

와이드 바와 나로드 바의 비율. 기본값: 3, 즉 와이드 바는 나로드 바보다 3배 넓습니다. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard에 사용됩니다. WideNarrowRatio 매개변수 값은 0 이하이어야 합니다.

### setXDimension() {#setxdimension}

x-차원은 BarCode 바 또는 공백 단위의 최소 너비입니다. 이를 증가시키면 전체 바코드 이미지 너비가 증가합니다. AutoSizeMode 속성이 AutoSizeMode.NEAREST 또는 AutoSizeMode.INTERPOLATION으로 설정된 경우 무시됩니다.

**Throws:** BarcodeException
