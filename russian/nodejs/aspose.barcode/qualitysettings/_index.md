---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "QualitySettings позволяет вручную настраивать качество распознавания и скорость."
type: docs
weight: 860
url: /ru/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро настроить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

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

## Методы

| Имя | Описание |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества хорошо распознаются в этом режиме. |
| [getHighQuality()](#gethighquality) *(static)* | Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества. |
| [getMaxQuality()](#getmaxquality) *(static)* | Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, даже некорректных барк |
| [getNormalQuality()](#getnormalquality) *(static)* | Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. Режим может использоваться для распознавания повреждённых |
| [getBarcodeQuality()](#getbarcodequality) | Режим, который позволяет методам распознавать элементы штрих‑кода с выбранным качеством. Элемент штрих‑кода с более низким качеством r |
| [getComplexBackground()](#getcomplexbackground) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [getDeconvolution()](#getdeconvolution) | Режим деконволюции (восстановление изображения), который определяет уровень деградации изображения. Изначально деконволюция является функцией |
| [getInverseImage()](#getinverseimage) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (luminance). |
| [getMinimalXDimension()](#getminimalxdimension) | Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Позволяет движку распознавать штрихкоды с неправильной контрольной суммой или некорректными значениями. Режим может использоваться для распознавания повреждённых |
| [setBarcodeQuality(value)](#setbarcodequality) | Режим, который позволяет методам распознавать элементы штрих‑кода с выбранным качеством. Элемент штрих‑кода с более низким качеством r |
| [setComplexBackground(value)](#setcomplexbackground) | Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях. |
| [setDeconvolution(value)](#setdeconvolution) | Режим деконволюции (восстановление изображения), который определяет уровень деградации изображения. Изначально деконволюция является функцией |
| [setInverseImage(value)](#setinverseimage) | Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (luminance). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса. |

### getHighPerformance() (static) {#gethighperformance}

Предустановка качества распознавания HighPerformance. Штрихкоды высокого качества хорошо распознаются в этом режиме.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Предустановка качества распознавания HighQuality. Эта предустановка разработана для штрихкодов низкого качества.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Предустановка качества распознавания MaxQuality. Эта предустановка разработана для распознавания всех возможных штрихкодов, включая некорректные штрихкоды. Этот пример показывает, как использовать режим MaxQuality reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Значение: предустановка качества распознавания MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Предустановка качества распознавания NormalQuality. Подходит для большинства штрихкодов

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с неправильным текстом.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода с более низким качеством требует более сложных методов, что замедляет распознавание.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Режим деконволюции (восстановление изображения), который определяет уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшённое (свернутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (luminance).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Позволяет движку распознавать штрихкоды с некорректной контрольной суммой или неверными значениями. Режим может использоваться для распознавания повреждённых штрихкодов с неправильным текстом.

| Параметр | Описание |
| --- | --- |
| значение | Позволяет движку распознавать некорректные штрихкоды. |

### setBarcodeQuality(value) {#setbarcodequality}

Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. Элемент штрихкода с более низким качеством требует более сложных методов, что замедляет распознавание.

| Параметр | Описание |
| --- | --- |
| значение | Режим, который включает методы распознавания элементов штрихкода с выбранным качеством. |

### setComplexBackground(value) {#setcomplexbackground}

Режим, который включает или отключает дополнительное распознавание цветных штрихкодов на цветных изображениях.

| Параметр | Описание |
| --- | --- |
| значение | Дополнительное распознавание цветных штрихкодов на цветных изображениях. |

### setDeconvolution(value) {#setdeconvolution}

Режим деконволюции (восстановление изображения), который определяет уровень деградации изображения. Изначально деконволюция — это функция, способная восстановить изображение, ухудшённое (свернутое) любой естественной функцией, такой как размытие, при получении изображения камерой. Поскольку мы не можем определить функцию, испортившую изображение, нам приходится проверять наиболее известные функции, такие как резкость или математическая морфология.

| Параметр | Описание |
| --- | --- |
| значение | Режим деконволюции, который определяет уровень деградации изображения. |

### setInverseImage(value) {#setinverseimage}

Режим, который включает или отключает дополнительное распознавание штрихкодов на изображениях с инвертированными цветами (luminance).

| Параметр | Описание |
| --- | --- |
| значение | Дополнительное распознавание штрихкодов на изображениях с инвертированными цветами |

### setMinimalXDimension(value) {#setminimalxdimension}

Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension.

| Параметр | Описание |
| --- | --- |
| значение | Минимальный размер XDimension в пикселях, который используется с UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Режим распознавания, который задает размер (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса.

| Параметр | Описание |
| --- | --- |
| значение | (от 1 до бесконечности) минимального элемента штрихкода: ячейка матрицы или полоса. |
