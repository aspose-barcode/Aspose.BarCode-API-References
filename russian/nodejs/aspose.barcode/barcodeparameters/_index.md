---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры генерации штрих‑кода."
type: docs
weight: 140
url: /ru/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Параметры генерации штрих‑кода.

```js
new BarcodeParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Параметры штрихкода AustralianPost. |
| [getAztec()](#getaztec) | Параметры Aztec. |
| [getBarColor()](#getbarcolor) | Цвет полос. |
| [getBarHeight()](#getbarheight) | Высота полос 1D штрихкодов в единицах. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Получить значение уменьшения полос, используемое для компенсации растекания чернил при печати. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Всегда отображать цифру контрольной суммы в человекочитаемом тексте для штрихкодов Code128 и GS1Code128. |
| [getCodabar()](#getcodabar) | Параметры Codabar. |
| [getCodablock()](#getcodablock) | Параметры Codablock. |
| [getCode16K()](#getcode16k) | Параметры Code16K. |
| [getCode128()](#getcode128) | Параметры Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Параметры Codetext. |
| [getCoupon()](#getcoupon) | Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Параметры Databar. |
| [getDataMatrix()](#getdatamatrix) | Параметры DataMatrix. |
| [getDotCode()](#getdotcode) | Параметры DotCode. |
| [getEnableEscape()](#getenableescape) | Указывает, объясняет ли символ "\" как символ экранирования в свойстве CodeText. Используется для Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Получает значение, указывающее, заполнены ли полосы. Только для 1D штрихкодов. Значение по умолчанию: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Параметры GS1 Composite Bar. Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext |
| [getHanXin()](#gethanxin) | Параметры HanXin. |
| [getITF()](#getitf) | Параметры ITF. |
| [getMaxiCode()](#getmaxicode) | Параметры MaxiCode. |
| [getPadding()](#getpadding) | Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Параметры PatchCode. |
| [getPdf417()](#getpdf417) | Параметры PDF417. |
| [getPostal()](#getpostal) | Почтовые параметры. Используется для Postnet, Planet. |
| [getQR()](#getqr) | Параметры QR. |
| [getSupplement()](#getsupplement) | Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Соотношение широких полос к узким. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, |
| [getXDimension()](#getxdimension) | x-dimension — это минимальная ширина единицы полос или пробелов BarCode. Увеличение этого параметра увеличит всю ширину штрихкода i |
| [isChecksumEnabled()](#ischecksumenabled) | Включить контрольную сумму при генерации 1D штрихкодов. По умолчанию считается Yes для символьных наборов, которые обязаны содержать контрольную сумму, как N |
| [setBarColor(value)](#setbarcolor) | Цвет полос. |
| [setBarHeight()](#setbarheight) | Высота полос 1D штрихкодов в единицах. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Устанавливает значение уменьшения полос, используемое для компенсации растекания чернил при печати. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Всегда отображать цифру контрольной суммы в человекочитаемом тексте для штрихкодов Code128 и GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Включить контрольную сумму при генерации 1D штрихкодов. По умолчанию считается Yes для символьных наборов, которые обязаны содержать контрольную сумму, как N |
| [setEnableEscape()](#setenableescape) | Указывает, объясняет ли символ "\" как символ экранирования в свойстве CodeText. Используется для Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Устанавливает значение, указывающее, заполнены ли полосы. Только для 1D штрихкодов. Значение по умолчанию: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Параметры GS1 Composite Bar. Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext |
| [setPadding()](#setpadding) | Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Соотношение широких полос к узким. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, P |
| [setXDimension()](#setxdimension) | x-dimension — это минимальная ширина единицы полос или пробелов BarCode. Увеличение этого параметра увеличит всю ширину штрихкода i |

### getAustralianPost() {#getaustralianpost}

Параметры штрихкода AustralianPost.

### getAztec() {#getaztec}

Параметры Aztec.

### getBarColor() {#getbarcolor}

Цвет полос.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Высота полос 1D штрихкодов в единицах. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Получить значение уменьшения полос, используемое для компенсации растекания чернил при печати.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Всегда отображать цифру контрольной суммы в человекочитаемом тексте для штрихкодов Code128 и GS1Code128.

### getCodabar() {#getcodabar}

Параметры Codabar.

### getCodablock() {#getcodablock}

Параметры Codablock.

### getCode16K() {#getcode16k}

Параметры Code16K.

### getCode128() {#getcode128}

Параметры Code128.

### getCodeTextParameters() {#getcodetextparameters}

Параметры Codetext.

### getCoupon() {#getcoupon}

Параметры купона. Используется для UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Параметры Databar.

### getDataMatrix() {#getdatamatrix}

Параметры DataMatrix.

### getDotCode() {#getdotcode}

Параметры DotCode.

### getEnableEscape() {#getenableescape}

Указывает, объясняет ли символ "\" как символ экранирования в свойстве CodeText. Используется для Pdf417, DataMatrix, Code128 только если EnableEscape равно true, "\" будет интерпретироваться как специальный символ экранирования. В противном случае "\" действует как обычный символ. Aspose.BarCode поддерживает ввод десятичного ASCII кода и мнемоники для символов управления ASCII. Например, \013 и \\CR обозначают CR.

### getFilledBars() {#getfilledbars}

Получает значение, указывающее, заполнены ли полосы. Только для 1D штрихкодов. Значение по умолчанию: true.

### getGS1CompositeBar() {#getgs1compositebar}

Параметры GS1 Composite Bar. Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext и 2D codetext разделены символом '/'

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

Параметры HanXin.

### getITF() {#getitf}

Параметры ITF.

### getMaxiCode() {#getmaxicode}

Параметры MaxiCode.

### getPadding() {#getpadding}

Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Параметры PatchCode.

### getPdf417() {#getpdf417}

Параметры PDF417.

### getPostal() {#getpostal}

Почтовые параметры. Используется для Postnet, Planet.

### getQR() {#getqr}

Параметры QR.

### getSupplement() {#getsupplement}

Дополнительные параметры. Используется для Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Соотношение широких полос к узким. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Значение параметра WideNarrowRatio меньше или равно 0.

### getXDimension() {#getxdimension}

x-dimension — это минимальная ширина единицы полос или пробелов BarCode. Увеличение этого параметра увеличит общую ширину изображения штрихкода. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Включить контрольную сумму при генерации 1‑мерных штрих‑кодов. По умолчанию считается «Да» для символьных наборов, которым обязательна контрольная сумма, и «Нет», где контрольная сумма возможна только. Контрольная сумма возможна для: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Контрольная сумма всегда используется: остальные символьные наборы.

### setBarColor(value) {#setbarcolor}

Цвет полос.

| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | String | Для цвета штрих‑кода значение по умолчанию: #000000. |

### setBarHeight() {#setbarheight}

Высота полос 1D штрихкодов в единицах. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Устанавливает значение уменьшения полос, используемое для компенсации растекания чернил при печати.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Всегда отображать цифру контрольной суммы в человекочитаемом тексте для штрихкодов Code128 и GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Включить контрольную сумму при генерации 1‑мерных штрих‑кодов. По умолчанию считается «Да» для символьных наборов, которым обязательна контрольная сумма, и «Нет», где контрольная сумма возможна только. Контрольная сумма возможна для: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Контрольная сумма всегда используется: остальные символьные наборы.

### setEnableEscape() {#setenableescape}

Указывает, объясняет ли символ \" как символ экранирования в свойстве CodeText. Используется только для Pdf417, DataMatrix, Code128. Если EnableEscape равно true, \" будет рассматриваться как специальный символ экранирования. В противном случае \" действует как обычный символ. Aspose.BarCode поддерживает десятичный ASCII‑код и мнемонику для символов управления ASCII. Например, \013 и \\CR обозначают CR.

### setFilledBars() {#setfilledbars}

Устанавливает значение, указывающее, заполнены ли полосы. Только для 1D штрихкодов. Значение по умолчанию: true.

### setGS1CompositeBar() {#setgs1compositebar}

Параметры GS1 Composite Bar. Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext и 2D codetext разделены символом '/'

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

Отступы штрихкода. Значение по умолчанию: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Соотношение широких и узких полос. Значение по умолчанию: 3, то есть широкие полосы в 3 раза шире узких. Используется для ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Параметр WideNarrowRatio имеет значение меньше или равно 0.

### setXDimension() {#setxdimension}

x-dimension — это минимальная ширина единицы полос или пробелов BarCode. Увеличение этого параметра увеличит общую ширину изображения штрихкода. Игнорируется, если свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
