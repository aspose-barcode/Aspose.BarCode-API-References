---
title: RecognitionAreaSettings
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: 
type: docs
weight: 21
url: /id/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Mendapatkan warna cat kerangka pemindai barcode |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Mendapatkan tinggi maksimum area pengenalan |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Mendapatkan lebar maksimum area pengenalan |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Mendapatkan gaya garis 1D BarcodeArea line |
| [getOneDLineColor()](#getOneDLineColor--) | Mendapatkan warna penanda pengenalan 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Mendapatkan lebar garis batas area 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Mendapatkan warna cat area pengenalan barcode |
| [getTopOffset()](#getTopOffset--) | Mendapatkan offset area pengenalan dari atas layar TODO dalam persen |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Mendapatkan gaya garis 2D BarcodeArea line |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Mengembalikan radius sudut yang dibulatkan |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Mendapatkan gaya batas 2D BarcodeArea |
| [getTwoDLineColor()](#getTwoDLineColor--) | Mendapatkan warna penanda pengenalan 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Mendapatkan lebar garis batas area 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Mendapatkan rasio antara lebar dan tinggi area pengenalan |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | menetapkan warna cat kerangka pemindai barcode |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Menetapkan tinggi maksimum area pengenalan |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Mengatur lebar maksimum area pengenalan |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Mengatur gaya baris 1D BarcodeArea |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Mengatur warna penanda pengenalan 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Mengatur lebar garis batas area 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Mengatur warna cat area pengenalan barcode |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Mengatur offset area pengenalan dari atas layar |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Mengatur gaya baris 2D BarcodeArea |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Mengembalikan radius sudut yang dibulatkan |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Mengatur gaya batas 2D BarcodeArea |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Mengatur warna penanda pengenalan 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Mengatur lebar garis batas area 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Mengatur rasio antara lebar dan tinggi area pengenalan |
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
| Parameter | Type | Deskripsi |
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


Mendapatkan warna cat kerangka pemindai barcode

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Mendapatkan tinggi maksimum area pengenalan

**Returns:**
float - tinggi maksimum area pengenalan
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Mendapatkan lebar maksimum area pengenalan

**Returns:**
float - lebar maksimum area pengenalan
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Mendapatkan gaya garis 1D BarcodeArea line

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Mendapatkan warna penanda pengenalan 1D

**Returns:**
int - warna penanda pengenalan 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Mendapatkan lebar garis batas area 1D

**Returns:**
float - lebar garis batas area 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Mendapatkan warna cat area pengenalan barcode

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Mendapatkan offset area pengenalan dari atas layar TODO dalam persen

**Returns:**
float - offset area pengenalan dari atas layar
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Mendapatkan gaya garis 2D BarcodeArea line

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Mengembalikan radius sudut yang dibulatkan

**Returns:**
float - radius sudut melengkung
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Mendapatkan gaya batas 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - gaya batas 2D BarcodeArea
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Mendapatkan warna penanda pengenalan 2D

**Returns:**
int - warna penanda pengenalan 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Mendapatkan lebar garis batas area 2D

**Returns:**
float - lebar garis batas area 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Mendapatkan rasio antara lebar dan tinggi area pengenalan

**Returns:**
float - rasio antara lebar dan tinggi area pengenalan
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
boolean - Visibilitas area pengenalan
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


menetapkan warna cat kerangka pemindai barcode

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Menetapkan tinggi maksimum area pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| maxAreaHeight | float | tinggi maksimum area pengenalan |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Mengatur lebar maksimum area pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| maxAreaWidth | float | lebar maksimum area pengenalan |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Mengatur gaya baris 1D BarcodeArea

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | gaya baris 1D BarcodeArea |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Mengatur warna penanda pengenalan 1D

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| oneDLineColor | int | warna penanda pengenalan 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Mengatur lebar garis batas area 1D

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| oneDLineWidth | float | lebar garis batas area 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Mengatur warna cat area pengenalan barcode

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionAreaColor | int | warna area pengenalan barcode. Jika warna tidak transparan, area pengenalan barcode tidak akan transparan |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibilitas area pengenalan |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Mengatur offset area pengenalan dari atas layar

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| topOffset | float | offset area pengenalan dari atas layar |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Mengatur gaya baris 2D BarcodeArea

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | gaya baris 2D BarcodeArea |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Mengembalikan radius sudut yang dibulatkan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| twoDAreaCornerRadius | float | radius sudut melengkung |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Mengatur gaya batas 2D BarcodeArea

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | gaya batas 2D BarcodeArea |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Mengatur warna penanda pengenalan 1D

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| twoDLineColor | int | warna penanda pengenalan 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Mengatur lebar garis batas area 2D

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| twoDLineWidth | float | lebar garis batas area 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Mengatur rasio antara lebar dan tinggi area pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| areaRatio | float | rasio antara lebar dan tinggi area pengenalan |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

