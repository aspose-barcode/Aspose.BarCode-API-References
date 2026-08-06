---
title: RecognitionAreaSettings
second_title: Справочник API Aspose.BarCode для Android через Java
description: 
type: docs
weight: 21
url: /ru/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Поля

| Поле | Описание |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Получает цвет краски рамки сканера штрихкода |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Получает максимальную высоту области распознавания |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Получает максимальную ширину области распознавания |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Получает стиль линии 1D BarcodeArea |
| [getOneDLineColor()](#getOneDLineColor--) | Получает цвет маркера 1D распознавания |
| [getOneDLineWidth()](#getOneDLineWidth--) | Получает ширину линии границы 1D области |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Получает цвет краски области распознавания штрихкода |
| [getTopOffset()](#getTopOffset--) | Получает смещение области распознавания от верхней части экрана (TODO в процентах) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Получает стиль линии 2D BarcodeArea |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Возвращает радиус скруглённого угла |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Получает стиль границы 2D BarcodeArea |
| [getTwoDLineColor()](#getTwoDLineColor--) | Получает цвет маркера 2D распознавания |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Получает ширину линии границы 2D области |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Получает соотношение между шириной и высотой области распознавания |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | устанавливает цвет краски рамки сканера штрихкода |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Устанавливает максимальную высоту области распознавания |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Устанавливает максимальную ширину области распознавания |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Устанавливает стиль линии 1D BarcodeArea |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Устанавливает цвет маркера распознавания 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Устанавливает ширину линии границы области 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Устанавливает цвет заливки области распознавания штрихкода |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Устанавливает смещение области распознавания от верхней части экрана |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Устанавливает стиль линии 2D BarcodeArea |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Возвращает радиус скруглённого угла |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Устанавливает стиль границы 2D BarcodeArea |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Устанавливает цвет маркера распознавания 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Устанавливает ширину линии границы области 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Устанавливает соотношение между шириной и высотой области распознавания |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionAreaSettings> CREATOR
```


### DEFAULT_1D_RECOGNITION_AREA_SETTINGS {#DEFAULT-1D-RECOGNITION-AREA-SETTINGS}
```
public static final RecognitionAreaSettings DEFAULT_1D_RECOGNITION_AREA_SETTINGS
```


### DEFAULT_2D_RECOGNITION_AREA_SETTINGS {#DEFAULT-2D-RECOGNITION-AREA-SETTINGS}
```
public static final RecognitionAreaSettings DEFAULT_2D_RECOGNITION_AREA_SETTINGS
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrameColor() {#getFrameColor--}
```
public int getFrameColor()
```


Получает цвет краски рамки сканера штрихкода

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Получает максимальную высоту области распознавания

**Returns:**
float - максимальная высота области распознавания
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Получает максимальную ширину области распознавания

**Returns:**
float - максимальная ширина области распознавания
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Получает стиль линии 1D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Получает цвет маркера 1D распознавания

**Returns:**
int - цвет маркера распознавания 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Получает ширину линии границы 1D области

**Returns:**
float - ширина линии границы области 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Получает цвет краски области распознавания штрихкода

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Получает смещение области распознавания от верхней части экрана (TODO в процентах)

**Returns:**
float - смещение области распознавания от верхней части экрана
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Получает стиль линии 2D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Возвращает радиус скруглённого угла

**Returns:**
float - радиус скруглённого угла
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Получает стиль границы 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - стиль границы 2D BarcodeArea
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Получает цвет маркера 2D распознавания

**Returns:**
int - цвет маркера распознавания 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Получает ширину линии границы 2D области

**Returns:**
float - ширина линии границы области 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Получает соотношение между шириной и высотой области распознавания

**Returns:**
float - соотношение между шириной и высотой области распознавания
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRecognizeOnlyInRecognitionArea() {#isRecognizeOnlyInRecognitionArea--}
```
public boolean isRecognizeOnlyInRecognitionArea()
```




**Returns:**
boolean - Видимость области распознавания
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFrameColor(int frameColor) {#setFrameColor-int-}
```
public void setFrameColor(int frameColor)
```


устанавливает цвет краски рамки сканера штрихкода

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Устанавливает максимальную высоту области распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAreaHeight | float | максимальная высота области распознавания |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Устанавливает максимальную ширину области распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAreaWidth | float | максимальная ширина зоны распознавания |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Устанавливает стиль линии 1D BarcodeArea

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | стиль линии области 1D штрихкода |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Устанавливает цвет маркера распознавания 1D

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oneDLineColor | int | цвет маркера распознавания 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Устанавливает ширину линии границы области 1D

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oneDLineWidth | float | ширина линии границы области 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Устанавливает цвет заливки области распознавания штрихкода

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognitionAreaColor | int | цвет зоны распознавания штрихкода. Если цвет не будет прозрачным, зона распознавания штрихкода также не будет прозрачной |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | видимость зоны распознавания |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Устанавливает смещение области распознавания от верхней части экрана

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| topOffset | float | смещение зоны распознавания от верхней части экрана |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Устанавливает стиль линии 2D BarcodeArea

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | стиль линии области 2D штрихкода |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Возвращает радиус скруглённого угла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| twoDAreaCornerRadius | float | радиус скругления углов |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Устанавливает стиль границы 2D BarcodeArea

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | стиль границы области 2D штрихкода |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Устанавливает цвет маркера распознавания 1D

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| twoDLineColor | int | цвет маркера распознавания 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Устанавливает ширину линии границы области 2D

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| twoDLineWidth | float | ширина линии границы области 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Устанавливает соотношение между шириной и высотой области распознавания

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| areaRatio | float | соотношение между шириной и высотой зоны распознавания |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

