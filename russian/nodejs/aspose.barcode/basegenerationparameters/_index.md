---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры генерации изображения штрих‑кода."
type: docs
weight: 160
url: /ru/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Параметры генерации изображения штрих‑кода.

```js
new BaseGenerationParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Цвет фона изображения штрихкода. Значение по умолчанию: #FFFFFF |
| [getBarcode()](#getbarcode) | Возвращает BarcodeParameters, содержащий все свойства штрихкода. |
| [getBorder()](#getborder) | Возвращает BorderParameters, содержащий все свойства конфигурации границы штрихкода. |
| [getCaptionAbove()](#getcaptionabove) | Подпись над изображением BarCode. См. CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Подпись под изображением BarCode. См. CaptionParameters. |
| [getImage()](#getimage) | Параметры изображения. См. ImageParameters. |
| [getImageHeight()](#getimageheight) | Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Возвращает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi. Параметр Resolution. |
| [getRotationAngle()](#getrotationangle) | Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота. Если Ro |
| [getUseAntiAlias()](#getuseantialias) | Возвращает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |
| [setAutoSizeMode()](#setautosizemode) | Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Цвет фона изображения штрихкода. Значение по умолчанию: #FFFFFF |
| [setImageHeight()](#setimageheight) | Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Устанавливает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi. Параметр Resolution |
| [setRotationAngle()](#setrotationangle) | Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота. Если Ro |
| [setUseAntiAlias()](#setuseantialias) | Устанавливает значение, указывающее, используется ли режим сглаживания при рендеринге изображения |

### getAutoSizeMode() {#getautosizemode}

Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Цвет фона изображения штрихкода. Значение по умолчанию: #FFFFFF

### getBarcode() {#getbarcode}

Возвращает BarcodeParameters, содержащий все свойства штрихкода.

### getBorder() {#getborder}

Возвращает BorderParameters, содержащий все свойства конфигурации границы штрихкода.

### getCaptionAbove() {#getcaptionabove}

Подпись над изображением BarCode. См. CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Подпись под изображением BarCode. См. CaptionParameters.

### getImage() {#getimage}

Параметры изображения. См. ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Возвращает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi. Значение параметра Resolution меньше или равно 0.

### getRotationAngle() {#getrotationangle}

Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения . Значение по умолчанию: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Возвращает значение, указывающее, используется ли режим сглаживания при рендеринге изображения

### setAutoSizeMode() {#setautosizemode}

Указывает различные типы режимов автоматического масштабирования. Значение по умолчанию: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Цвет фона изображения штрихкода. Значение по умолчанию: #FFFFFF

### setImageHeight() {#setimageheight}

Высота изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

Ширина изображения BarCode, когда свойство AutoSizeMode установлено в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Устанавливает разрешение изображения BarCode. Одно значение для обеих измерений. Значение по умолчанию: 96 dpi. Значение параметра Resolution меньше или равно 0.

### setRotationAngle() {#setrotationangle}

Угол поворота изображения BarCode, измеряется в градусах, например RotationAngle = 0 или RotationAngle = 360 означает отсутствие поворота. Если RotationAngle НЕ равен 90, 180, 270 или 0, это может усложнить сканеру чтение изображения. Значение по умолчанию: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Устанавливает значение, указывающее, используется ли режим сглаживания при рендеринге изображения
