---
title: RecognitionAreaSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 21
url: /ja/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## フィールド

| フィールド | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | バーコードスキャナフレームの塗装色を取得します |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | 認識領域の最大高さを取得します |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | 認識領域の最大幅を取得します |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | 1D BarcodeArea line のスタイルを取得します |
| [getOneDLineColor()](#getOneDLineColor--) | 1D 認識マーカーの色を取得します |
| [getOneDLineWidth()](#getOneDLineWidth--) | 1D エリア境界ラインの幅を取得します |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | バーコード認識領域の塗装色を取得します |
| [getTopOffset()](#getTopOffset--) | 画面上部からの認識領域オフセットを取得します TODO in percents |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | 2D BarcodeArea line のスタイルを取得します |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | 丸みを帯びたコーナー半径を返します |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | 2D BarcodeArea border のスタイルを取得します |
| [getTwoDLineColor()](#getTwoDLineColor--) | 2D 認識マーカーの色を取得します |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | 2D エリア境界ラインの幅を取得します |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | 認識領域の幅と高さの比率を取得します |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | バーコードスキャナフレームの塗装色を設定します |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | 認識領域の最大高さを設定します |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | 認識領域の最大幅を設定します |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 1D バーコード領域ラインのスタイルを設定します |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | 1D 認識マーカーの色を設定します |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | 1D エリア境界ラインの幅を設定します |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | バーコード認識領域の塗装色を設定します |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | 画面上部から認識領域のオフセットを設定します |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 2D バーコード領域ラインのスタイルを設定します |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | 丸みを帯びたコーナー半径を返します |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | 2D バーコード領域の境界のスタイルを設定します |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | 1D 認識マーカーの色を設定します |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | 2D エリア境界ラインの幅を設定します |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | 認識領域の幅と高さの比率を設定します |
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
| Parameter | Type | Description |
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


バーコードスキャナフレームの塗装色を取得します

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


認識領域の最大高さを取得します

**Returns:**
float - 認識領域の最大高さ
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


認識領域の最大幅を取得します

**Returns:**
float - 認識領域の最大幅
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


1D BarcodeArea line のスタイルを取得します

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


1D 認識マーカーの色を取得します

**Returns:**
int - 1D 認識マーカーの色
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


1D エリア境界ラインの幅を取得します

**Returns:**
float - 1D エリア境界ラインの幅
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


バーコード認識領域の塗装色を取得します

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


画面上部からの認識領域オフセットを取得します TODO in percents

**Returns:**
float - 画面上部から認識領域のオフセット
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


2D BarcodeArea line のスタイルを取得します

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


丸みを帯びたコーナー半径を返します

**Returns:**
float - 角丸半径
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


2D BarcodeArea border のスタイルを取得します

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - 2D バーコード領域の境界のスタイル
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


2D 認識マーカーの色を取得します

**Returns:**
int - 1D 認識マーカーの色
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


2D エリア境界ラインの幅を取得します

**Returns:**
float - 2D エリア境界ラインの幅
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


認識領域の幅と高さの比率を取得します

**Returns:**
float - 認識領域の幅と高さの比率
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
boolean - 認識領域の可視性
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


バーコードスキャナフレームの塗装色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


認識領域の最大高さを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAreaHeight | float | 認識領域の最大高さ |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


認識領域の最大幅を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAreaWidth | float | 認識領域の最大幅 |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


1D バーコード領域ラインのスタイルを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 1D バーコード領域ラインのスタイル |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


1D 認識マーカーの色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDLineColor | int | 1D 認識マーカーの色 |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


1D エリア境界ラインの幅を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDLineWidth | float | 1D 領域の境界線の幅 |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


バーコード認識領域の塗装色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionAreaColor | int | バーコード認識領域の色。色が透明でない場合、バーコード認識領域は透明になりません |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | 認識領域の可視性 |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


画面上部から認識領域のオフセットを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topOffset | float | 画面上部からの認識領域オフセット |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


2D バーコード領域ラインのスタイルを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 2D バーコード領域ラインのスタイル |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


丸みを帯びたコーナー半径を返します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaCornerRadius | float | 丸みを帯びた角の半径 |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


2D バーコード領域の境界のスタイルを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | 2D バーコード領域境界のスタイル |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


1D 認識マーカーの色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDLineColor | int | 1D 認識マーカーの色 |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


2D エリア境界ラインの幅を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDLineWidth | float | 2D 領域境界線の幅 |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


認識領域の幅と高さの比率を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| areaRatio | float | 認識領域の幅と高さの比率 |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

