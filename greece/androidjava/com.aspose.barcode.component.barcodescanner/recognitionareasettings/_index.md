---
title: RecognitionAreaSettings
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: 
type: docs
weight: 21
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Λαμβάνει το χρώμα βαφής του πλαισίου του σαρωτή barcode |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Λαμβάνει το μέγιστο ύψος της περιοχής αναγνώρισης |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Λαμβάνει το μέγιστο πλάτος της περιοχής αναγνώρισης |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Λαμβάνει το στυλ της γραμμής 1D BarcodeArea |
| [getOneDLineColor()](#getOneDLineColor--) | Λαμβάνει το χρώμα του δείκτη αναγνώρισης 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Λαμβάνει το χρώμα βαφής της περιοχής αναγνώρισης barcode |
| [getTopOffset()](#getTopOffset--) | Λαμβάνει την απόσταση της περιοχής αναγνώρισης από την κορυφή της οθόνης TODO σε ποσοστά |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Λαμβάνει το στυλ της γραμμής 2D BarcodeArea |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Λαμβάνει το στυλ του περιγράμματος 2D BarcodeArea |
| [getTwoDLineColor()](#getTwoDLineColor--) | Λαμβάνει το χρώμα του δείκτη αναγνώρισης 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Λαμβάνει την αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | ορίζει το χρώμα βαφής του πλαισίου του σαρωτή barcode |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Ορίζει το μέγιστο ύψος της περιοχής αναγνώρισης |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Sets the recognition area max width |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Sets style of 1D BarcodeArea line |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Sets the color of 1D recognition marker |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Sets the width of 1D area border line |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Sets the paint color of barcode recognition area |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Sets the recognition area offset from top of screen |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Sets style of 2D BarcodeArea line |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Sets style of 2D BarcodeArea border |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Sets the color of 1D recognition marker |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Sets the width of 2D area border line |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Sets ratio between width and height of the recognition area |
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
| Parameter | Type | Περιγραφή |
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


Λαμβάνει το χρώμα βαφής του πλαισίου του σαρωτή barcode

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Λαμβάνει το μέγιστο ύψος της περιοχής αναγνώρισης

**Returns:**
float - the recognition area max height
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Λαμβάνει το μέγιστο πλάτος της περιοχής αναγνώρισης

**Returns:**
float - the recognition area max width
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Λαμβάνει το στυλ της γραμμής 1D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Λαμβάνει το χρώμα του δείκτη αναγνώρισης 1D

**Returns:**
int - the color of 1D recognition marker
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 1D

**Returns:**
float - the width of 1D area border line
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Λαμβάνει το χρώμα βαφής της περιοχής αναγνώρισης barcode

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Λαμβάνει την απόσταση της περιοχής αναγνώρισης από την κορυφή της οθόνης TODO σε ποσοστά

**Returns:**
float - the recognition area offset from top of screen
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Λαμβάνει το στυλ της γραμμής 2D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών

**Returns:**
float - rounded corner radius
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Λαμβάνει το στυλ του περιγράμματος 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - style of 2D BarcodeArea border
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Λαμβάνει το χρώμα του δείκτη αναγνώρισης 2D

**Returns:**
int - the color of 1D recognition marker
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 2D

**Returns:**
float - the width of 2D area border line
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Λαμβάνει την αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης

**Returns:**
float - ratio between width and height of the recognition area
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
boolean - Visibility of the recognition area
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


ορίζει το χρώμα βαφής του πλαισίου του σαρωτή barcode

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Ορίζει το μέγιστο ύψος της περιοχής αναγνώρισης

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| maxAreaHeight | float | the recognition area max height |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Sets the recognition area max width

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| maxAreaWidth | float | the recognition area max width |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Sets style of 1D BarcodeArea line

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 1D BarcodeArea line |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Sets the color of 1D recognition marker

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| oneDLineColor | int | the color of 1D recognition marker |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Sets the width of 1D area border line

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| oneDLineWidth | float | the width of 1D area border line |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Sets the paint color of barcode recognition area

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognitionAreaColor | int | color of barcode recognition area. If color will not transparent, barcode recognition area will not transparent |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibility of the recognition area |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Sets the recognition area offset from top of screen

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| topOffset | float | the recognition area offset from top of screen |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Sets style of 2D BarcodeArea line

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 2D BarcodeArea line |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| twoDAreaCornerRadius | float | rounded corner radius |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Sets style of 2D BarcodeArea border

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | style of 2D BarcodeArea border |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Sets the color of 1D recognition marker

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| twoDLineColor | int | the color of 1D recognition marker |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Sets the width of 2D area border line

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| twoDLineWidth | float | the width of 2D area border line |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Sets ratio between width and height of the recognition area

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| areaRatio | float | ratio between width and height of the recognition area |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

