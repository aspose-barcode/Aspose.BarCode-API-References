---
title: "RecognitionAreaSettings"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: 
type: docs
weight: 21
url: /zh/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | 获取条形码扫描仪框架的绘制颜色 |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | 获取识别区域的最大高度 |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | 获取识别区域的最大宽度 |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | 获取 1D 条形码区域线的样式 |
| [getOneDLineColor()](#getOneDLineColor--) | 获取 1D 识别标记的颜色 |
| [getOneDLineWidth()](#getOneDLineWidth--) | 获取 1D 区域边框线的宽度 |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | 获取条形码识别区域的绘制颜色 |
| [getTopOffset()](#getTopOffset--) | 获取识别区域相对于屏幕顶部的偏移量（TODO，以百分比表示） |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | 获取 2D 条形码区域线的样式 |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | 返回圆角半径 |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | 获取 2D 条形码区域边框的样式 |
| [getTwoDLineColor()](#getTwoDLineColor--) | 获取 2D 识别标记的颜色 |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | 获取 2D 区域边框线的宽度 |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | 获取识别区域宽高比 |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | 设置条形码扫描仪框架的绘制颜色 |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | 设置识别区域的最大高度 |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | 设置识别区域的最大宽度 |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 设置 1D BarcodeArea 线的样式 |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | 设置 1D 识别标记的颜色 |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | 设置 1D 区域边框线的宽度 |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | 设置 条形码识别区域的绘制颜色 |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | 设置 识别区域相对于屏幕顶部的偏移量 |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 设置 2D BarcodeArea 线的样式 |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | 返回圆角半径 |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | 设置 2D BarcodeArea 边框的样式 |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | 设置 1D 识别标记的颜色 |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | 设置 2D 区域边框线的宽度 |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | 设置 识别区域宽度与高度的比例 |
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
整数
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


获取条形码扫描仪框架的绘制颜色

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


获取识别区域的最大高度

**Returns:**
float - 识别区域的最大高度
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


获取识别区域的最大宽度

**Returns:**
float - 识别区域的最大宽度
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


获取 1D 条形码区域线的样式

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


获取 1D 识别标记的颜色

**Returns:**
int - 1D 识别标记的颜色
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


获取 1D 区域边框线的宽度

**Returns:**
float - 1D 区域边框线的宽度
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


获取条形码识别区域的绘制颜色

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


获取识别区域相对于屏幕顶部的偏移量（TODO，以百分比表示）

**Returns:**
float - 识别区域相对于屏幕顶部的偏移量
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


获取 2D 条形码区域线的样式

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


返回圆角半径

**Returns:**
float - 圆角半径
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


获取 2D 条形码区域边框的样式

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - 2D BarcodeArea 边框的样式
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


获取 2D 识别标记的颜色

**Returns:**
int - 1D 识别标记的颜色
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


获取 2D 区域边框线的宽度

**Returns:**
float - 2D 区域边框线的宽度
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


获取识别区域宽高比

**Returns:**
float - 识别区域宽度与高度的比例
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
整数
### isRecognizeOnlyInRecognitionArea() {#isRecognizeOnlyInRecognitionArea--}
```
public boolean isRecognizeOnlyInRecognitionArea()
```




**Returns:**
boolean - 识别区域的可见性
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


设置条形码扫描仪框架的绘制颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frameColor | 整数 |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


设置识别区域的最大高度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxAreaHeight | float | 识别区域的最大高度 |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


设置识别区域的最大宽度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxAreaWidth | float | 识别区域的最大宽度 |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


设置 1D BarcodeArea 线的样式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 1D 条形码区域线的样式 |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


设置 1D 识别标记的颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oneDLineColor | 整数 | 1D 识别标记的颜色 |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


设置 1D 区域边框线的宽度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oneDLineWidth | float | 1D 区域边框线的宽度 |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


设置 条形码识别区域的绘制颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionAreaColor | 整数 | 条形码识别区域的颜色。如果颜色不透明，条形码识别区域也将不透明 |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | 布尔 | 识别区域的可见性 |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


设置 识别区域相对于屏幕顶部的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| topOffset | float | 识别区域距屏幕顶部的偏移 |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


设置 2D BarcodeArea 线的样式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 2D 条形码区域线的样式 |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


返回圆角半径

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| twoDAreaCornerRadius | float | 圆角半径 |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


设置 2D BarcodeArea 边框的样式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | 2D 条形码区域边框的样式 |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


设置 1D 识别标记的颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| twoDLineColor | 整数 | 1D 识别标记的颜色 |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


设置 2D 区域边框线的宽度

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| twoDLineWidth | float | 2D 区域边框线的宽度 |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


设置 识别区域宽度与高度的比例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| areaRatio | float | 识别区域宽度与高度的比例 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | 整数 |  |

