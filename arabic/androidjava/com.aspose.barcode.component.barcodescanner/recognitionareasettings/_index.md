---
title: RecognitionAreaSettings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: 
type: docs
weight: 21
url: /ar/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | يحصل على لون الطلاء لإطار ماسح الباركود |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | يحصل على أقصى ارتفاع لمنطقة التعرف |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | يحصل على أقصى عرض لمنطقة التعرف |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | يحصل على نمط خط 1D BarcodeArea |
| [getOneDLineColor()](#getOneDLineColor--) | يحصل على لون 1D recognition marker |
| [getOneDLineWidth()](#getOneDLineWidth--) | يحصل على عرض خط حدود 1D area |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | يحصل على لون الطلاء لمنطقة التعرف على الباركود |
| [getTopOffset()](#getTopOffset--) | يحصل على إزاحة منطقة التعرف من أعلى الشاشة TODO بالنسب المئوية |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | يحصل على نمط خط 2D BarcodeArea |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | يعيد نصف قطر الزاوية المدورة |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | يحصل على نمط حد 2D BarcodeArea |
| [getTwoDLineColor()](#getTwoDLineColor--) | يحصل على لون 2D recognition marker |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | يحصل على عرض خط حدود منطقة 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | يحصل على النسبة بين العرض والارتفاع لمنطقة التعرف |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | يضبط لون الطلاء لإطار ماسح الباركود |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | يضبط أقصى ارتفاع لمنطقة التعرف |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | يضبط الحد الأقصى لعرض منطقة التعرف |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | يضبط نمط خط 1D BarcodeArea |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | يضبط لون علامة التعرف 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | يضبط عرض خط حدود منطقة 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | يضبط لون الطلاء لمنطقة التعرف على الباركود |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | يضبط إزاحة منطقة التعرف من أعلى الشاشة |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | يضبط نمط خط 2D BarcodeArea |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | يعيد نصف قطر الزاوية المدورة |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | يضبط نمط حدود 2D BarcodeArea |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | يضبط لون علامة التعرف 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | يضبط عرض خط حدود منطقة 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | يضبط النسبة بين العرض والارتفاع لمنطقة التعرف |
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
| Parameter | Type | الوصف |
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


يحصل على لون الطلاء لإطار ماسح الباركود

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


يحصل على أقصى ارتفاع لمنطقة التعرف

**Returns:**
float - الحد الأقصى لارتفاع منطقة التعرف
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


يحصل على أقصى عرض لمنطقة التعرف

**Returns:**
float - الحد الأقصى لعرض منطقة التعرف
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


يحصل على نمط خط 1D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


يحصل على لون 1D recognition marker

**Returns:**
int - لون علامة التعرف 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


يحصل على عرض خط حدود 1D area

**Returns:**
float - عرض خط حدود منطقة 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


يحصل على لون الطلاء لمنطقة التعرف على الباركود

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


يحصل على إزاحة منطقة التعرف من أعلى الشاشة TODO بالنسب المئوية

**Returns:**
float - إزاحة منطقة التعرف من أعلى الشاشة
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


يحصل على نمط خط 2D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


يعيد نصف قطر الزاوية المدورة

**Returns:**
float - نصف قطر الزاوية المستديرة
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


يحصل على نمط حد 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - نمط حدود 2D BarcodeArea
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


يحصل على لون 2D recognition marker

**Returns:**
int - لون علامة التعرف 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


يحصل على عرض خط حدود منطقة 2D

**Returns:**
float - عرض خط حدود منطقة 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


يحصل على النسبة بين العرض والارتفاع لمنطقة التعرف

**Returns:**
float - النسبة بين العرض والارتفاع لمنطقة التعرف
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
boolean - إظهار منطقة التعرف
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


يضبط لون الطلاء لإطار ماسح الباركود

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


يضبط أقصى ارتفاع لمنطقة التعرف

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| maxAreaHeight | float | الحد الأقصى لارتفاع منطقة التعرف |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


يضبط الحد الأقصى لعرض منطقة التعرف

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| maxAreaWidth | float | العرض الأقصى لمنطقة التعرف |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


يضبط نمط خط 1D BarcodeArea

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | نمط خط منطقة الباركود أحادي الأبعاد |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


يضبط لون علامة التعرف 1D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| oneDLineColor | int | لون علامة التعرف أحادي الأبعاد |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


يضبط عرض خط حدود منطقة 1D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| oneDLineWidth | float | عرض خط حدود المنطقة أحادي الأبعاد |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


يضبط لون الطلاء لمنطقة التعرف على الباركود

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognitionAreaColor | int | لون منطقة التعرف على الباركود. إذا لم يكن اللون شفافًا، فإن منطقة التعرف على الباركود لن تكون شفافة |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | إظهار منطقة التعرف |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


يضبط إزاحة منطقة التعرف من أعلى الشاشة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| topOffset | float | إزاحة منطقة التعرف من أعلى الشاشة |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


يضبط نمط خط 2D BarcodeArea

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | نمط خط منطقة الباركود ثنائي الأبعاد |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


يعيد نصف قطر الزاوية المدورة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| twoDAreaCornerRadius | float | نصف قطر الزاوية المستديرة |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


يضبط نمط حدود 2D BarcodeArea

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | نمط حدود منطقة الباركود ثنائي الأبعاد |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


يضبط لون علامة التعرف 1D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| twoDLineColor | int | لون علامة التعرف أحادي الأبعاد |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


يضبط عرض خط حدود منطقة 2D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| twoDLineWidth | float | عرض خط حدود منطقة ثنائي الأبعاد |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


يضبط النسبة بين العرض والارتفاع لمنطقة التعرف

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| areaRatio | float | النسبة بين عرض وارتفاع منطقة التعرف |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

