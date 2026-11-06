---
title: "RecognitionAreaSettings"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Λαμβάνει το λόγο μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | ορίζει το χρώμα βαφής του πλαισίου του σαρωτή barcode |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Ορίζει το μέγιστο ύψος της περιοχής αναγνώρισης |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Ορίζει το μέγιστο πλάτος της περιοχής αναγνώρισης |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ορίζει το στυλ της γραμμής 1D BarcodeArea |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Ορίζει το χρώμα του δείκτη αναγνώρισης 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Ορίζει το πλάτος της γραμμής περιγράμματος περιοχής 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Ορίζει το χρώμα ζωγραφικής της περιοχής αναγνώρισης barcode |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Ορίζει τη μετατόπιση της περιοχής αναγνώρισης από την κορυφή της οθόνης |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ορίζει το στυλ της γραμμής 2D BarcodeArea |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Ορίζει το στυλ του περιγράμματος 2D BarcodeArea |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Ορίζει το χρώμα του δείκτη αναγνώρισης 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Ορίζει το πλάτος της γραμμής περιγράμματος περιοχής 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Ορίζει την αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
float - το μέγιστο ύψος της περιοχής αναγνώρισης
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Λαμβάνει το μέγιστο πλάτος της περιοχής αναγνώρισης

**Returns:**
float - το μέγιστο πλάτος της περιοχής αναγνώρισης
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
int - το χρώμα του δείκτη αναγνώρισης 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 1D

**Returns:**
float - το πλάτος της γραμμής περιγράμματος περιοχής 1D
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
float - η μετατόπιση της περιοχής αναγνώρισης από την κορυφή της οθόνης
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
float - ακτίνα στρογγυλεμένων γωνιών
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Λαμβάνει το στυλ του περιγράμματος 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - στυλ του περιγράμματος 2D BarcodeArea
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Λαμβάνει το χρώμα του δείκτη αναγνώρισης 2D

**Returns:**
int - το χρώμα του δείκτη αναγνώρισης 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Λαμβάνει το πλάτος της γραμμής περιγράμματος της περιοχής 2D

**Returns:**
float - το πλάτος της γραμμής περιγράμματος περιοχής 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Λαμβάνει το λόγο μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης

**Returns:**
float - αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης
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
boolean - Ορατότητα της περιοχής αναγνώρισης
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Ορίζει το μέγιστο ύψος της περιοχής αναγνώρισης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAreaHeight | float | το μέγιστο ύψος της περιοχής αναγνώρισης |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Ορίζει το μέγιστο πλάτος της περιοχής αναγνώρισης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAreaWidth | float | το μέγιστο πλάτος της περιοχής αναγνώρισης |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Ορίζει το στυλ της γραμμής 1D BarcodeArea

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | στυλ γραμμής περιοχής BarcodeArea 1D |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Ορίζει το χρώμα του δείκτη αναγνώρισης 1D

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oneDLineColor | int | το χρώμα του δείκτη αναγνώρισης 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Ορίζει το πλάτος της γραμμής περιγράμματος περιοχής 1D

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oneDLineWidth | float | το πλάτος της γραμμής περιγράμματος περιοχής 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Ορίζει το χρώμα ζωγραφικής της περιοχής αναγνώρισης barcode

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognitionAreaColor | int | χρώμα περιοχής αναγνώρισης barcode. Εάν το χρώμα δεν είναι διαφανές, η περιοχή αναγνώρισης barcode δεν θα είναι διαφανής |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Ορατότητα της περιοχής αναγνώρισης |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Ορίζει τη μετατόπιση της περιοχής αναγνώρισης από την κορυφή της οθόνης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| topOffset | float | η μετατόπιση της περιοχής αναγνώρισης από την κορυφή της οθόνης |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Ορίζει το στυλ της γραμμής 2D BarcodeArea

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | στυλ γραμμής περιοχής BarcodeArea 2D |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Επιστρέφει την ακτίνα στρογγυλεμένων γωνιών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| twoDAreaCornerRadius | float | ακτίνα στρογγυλεμένων γωνιών |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Ορίζει το στυλ του περιγράμματος 2D BarcodeArea

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | στυλ περιγράμματος περιοχής BarcodeArea 2D |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Ορίζει το χρώμα του δείκτη αναγνώρισης 1D

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| twoDLineColor | int | το χρώμα του δείκτη αναγνώρισης 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Ορίζει το πλάτος της γραμμής περιγράμματος περιοχής 2D

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| twoDLineWidth | float | το πλάτος της γραμμής περιγράμματος περιοχής 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Ορίζει την αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| areaRatio | float | αναλογία μεταξύ πλάτους και ύψους της περιοχής αναγνώρισης |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

