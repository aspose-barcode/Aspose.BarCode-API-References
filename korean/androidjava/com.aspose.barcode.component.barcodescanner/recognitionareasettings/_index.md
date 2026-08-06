---
title: RecognitionAreaSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 21
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | 바코드 스캐너 프레임의 페인트 색상을 가져옵니다 |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | 인식 영역의 최대 높이를 가져옵니다 |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | 인식 영역의 최대 너비를 가져옵니다 |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | 1D BarcodeArea 라인의 스타일을 가져옵니다 |
| [getOneDLineColor()](#getOneDLineColor--) | 1D 인식 마커의 색상을 가져옵니다 |
| [getOneDLineWidth()](#getOneDLineWidth--) | 1D 영역 테두리 라인의 너비를 가져옵니다 |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | 바코드 인식 영역의 페인트 색상을 가져옵니다 |
| [getTopOffset()](#getTopOffset--) | 화면 상단에서 인식 영역 오프셋을 퍼센트 단위로 가져옵니다 (TODO) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | 2D BarcodeArea 라인의 스타일을 가져옵니다 |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | 반올림된 모서리 반경을 반환합니다 |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | 2D BarcodeArea 테두리의 스타일을 가져옵니다 |
| [getTwoDLineColor()](#getTwoDLineColor--) | 2D 인식 마커의 색상을 가져옵니다 |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | 2D 영역 테두리 라인의 너비를 가져옵니다 |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | 인식 영역의 너비와 높이 사이 비율을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | 바코드 스캐너 프레임의 페인트 색상을 설정합니다 |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | 인식 영역의 최대 높이를 설정합니다 |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | 인식 영역 최대 너비를 설정합니다 |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 1D BarcodeArea 라인의 스타일을 설정합니다 |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | 1D 인식 마커의 색상을 설정합니다 |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | 1D 영역 테두리 라인의 너비를 설정합니다 |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | 바코드 인식 영역의 페인트 색상을 설정합니다 |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | 화면 상단으로부터 인식 영역 오프셋을 설정합니다 |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 2D BarcodeArea 라인의 스타일을 설정합니다 |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | 반올림된 모서리 반경을 반환합니다 |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | 2D BarcodeArea 테두리의 스타일을 설정합니다 |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | 1D 인식 마커의 색상을 설정합니다 |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | 2D 영역 테두리 라인의 너비를 설정합니다 |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | 인식 영역의 너비와 높이 비율을 설정합니다 |
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
| Parameter | Type | 설명 |
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


바코드 스캐너 프레임의 페인트 색상을 가져옵니다

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


인식 영역의 최대 높이를 가져옵니다

**Returns:**
float - 인식 영역 최대 높이
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


인식 영역의 최대 너비를 가져옵니다

**Returns:**
float - 인식 영역 최대 너비
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


1D BarcodeArea 라인의 스타일을 가져옵니다

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


1D 인식 마커의 색상을 가져옵니다

**Returns:**
int - 1D 인식 마커의 색상
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


1D 영역 테두리 라인의 너비를 가져옵니다

**Returns:**
float - 1D 영역 테두리 라인의 너비
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


바코드 인식 영역의 페인트 색상을 가져옵니다

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


화면 상단에서 인식 영역 오프셋을 퍼센트 단위로 가져옵니다 (TODO)

**Returns:**
float - 화면 상단으로부터 인식 영역 오프셋
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


2D BarcodeArea 라인의 스타일을 가져옵니다

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


반올림된 모서리 반경을 반환합니다

**Returns:**
float - 둥근 모서리 반경
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


2D BarcodeArea 테두리의 스타일을 가져옵니다

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - 2D BarcodeArea 테두리의 스타일
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


2D 인식 마커의 색상을 가져옵니다

**Returns:**
int - 1D 인식 마커의 색상
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


2D 영역 테두리 라인의 너비를 가져옵니다

**Returns:**
float - 2D 영역 테두리 라인의 너비
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


인식 영역의 너비와 높이 사이 비율을 가져옵니다

**Returns:**
float - 인식 영역의 너비와 높이 비율
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
boolean - 인식 영역의 가시성
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


바코드 스캐너 프레임의 페인트 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


인식 영역의 최대 높이를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| maxAreaHeight | float | 인식 영역 최대 높이 |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


인식 영역 최대 너비를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| maxAreaWidth | float | 인식 영역 최대 너비 |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


1D BarcodeArea 라인의 스타일을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 1D 바코드 영역 라인의 스타일 |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


1D 인식 마커의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| oneDLineColor | int | 1D 인식 마커의 색상 |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


1D 영역 테두리 라인의 너비를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| oneDLineWidth | float | 1D 영역 테두리 라인의 너비 |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


바코드 인식 영역의 페인트 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionAreaColor | int | 바코드 인식 영역의 색상. 색상이 투명하지 않으면 바코드 인식 영역도 투명하지 않습니다. |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | 인식 영역의 가시성 |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


화면 상단으로부터 인식 영역 오프셋을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| topOffset | float | 스크린 상단으로부터 인식 영역의 오프셋 |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


2D BarcodeArea 라인의 스타일을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 2D 바코드 영역 라인의 스타일 |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


반올림된 모서리 반경을 반환합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| twoDAreaCornerRadius | float | 둥근 모서리 반경 |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


2D BarcodeArea 테두리의 스타일을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | 2D 바코드 영역 테두리의 스타일 |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


1D 인식 마커의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| twoDLineColor | int | 1D 인식 마커의 색상 |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


2D 영역 테두리 라인의 너비를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| twoDLineWidth | float | 2D 영역 테두리 라인의 너비 |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


인식 영역의 너비와 높이 비율을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| areaRatio | float | 인식 영역의 너비와 높이 비율 |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

