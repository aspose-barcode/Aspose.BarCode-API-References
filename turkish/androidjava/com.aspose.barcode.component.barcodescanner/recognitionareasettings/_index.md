---
title: "RecognitionAreaSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: 
type: docs
weight: 21
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Barkod tarayıcı çerçevesinin boya rengini alır |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Tanıma alanının maksimum yüksekliğini alır |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Tanıma alanının maksimum genişliğini alır |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | 1D BarcodeArea satırının stilini alır |
| [getOneDLineColor()](#getOneDLineColor--) | 1D tanıma işaretçisinin rengini alır |
| [getOneDLineWidth()](#getOneDLineWidth--) | 1D alan kenar çizgisinin genişliğini alır |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Barkod tanıma alanının boya rengini alır |
| [getTopOffset()](#getTopOffset--) | Ekranın üstünden tanıma alanının ofsetini yüzde olarak alır TODO |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | 2D BarcodeArea satırının stilini alır |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Yuvarlatılmış köşe yarıçapını döndürür |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | 2D BarcodeArea kenarının stilini alır |
| [getTwoDLineColor()](#getTwoDLineColor--) | 2D tanıma işaretçisinin rengini alır |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | 2D alan kenar çizgisinin genişliğini alır |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Tanıma alanının genişlik ve yükseklik oranını alır |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | barkod tarayıcı çerçevesinin boya rengini ayarlar |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Tanıma alanının maksimum yüksekliğini ayarlar |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Tanıma alanının maksimum genişliğini ayarlar |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 1D BarcodeArea satırının stilini ayarlar |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | 1D tanıma işaretçisinin rengini ayarlar |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | 1D alan kenar çizgisinin genişliğini ayarlar |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Barkod tanıma alanının boya rengini ayarlar |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Tanıma alanının ekranın üstünden ofsetini ayarlar |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 2D BarcodeArea satırının stilini ayarlar |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Yuvarlatılmış köşe yarıçapını döndürür |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | 2D BarcodeArea kenarının stilini ayarlar |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | 1D tanıma işaretçisinin rengini ayarlar |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | 2D alan kenar çizgisinin genişliğini ayarlar |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Tanıma alanının genişlik ve yükseklik oranını ayarlar |
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
| Parametre | Tür | Açıklama |
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


Barkod tarayıcı çerçevesinin boya rengini alır

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Tanıma alanının maksimum yüksekliğini alır

**Returns:**
float - tanıma alanının maksimum yüksekliği
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Tanıma alanının maksimum genişliğini alır

**Returns:**
float - tanıma alanının maksimum genişliği
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


1D BarcodeArea satırının stilini alır

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


1D tanıma işaretçisinin rengini alır

**Returns:**
int - 1D tanıma işaretçisinin rengi
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


1D alan kenar çizgisinin genişliğini alır

**Returns:**
float - 1D alan kenar çizgisinin genişliği
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Barkod tanıma alanının boya rengini alır

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Ekranın üstünden tanıma alanının ofsetini yüzde olarak alır TODO

**Returns:**
float - tanıma alanının ekranın üstünden ofseti
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


2D BarcodeArea satırının stilini alır

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Yuvarlatılmış köşe yarıçapını döndürür

**Returns:**
float - yuvarlatılmış köşe yarıçapı
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


2D BarcodeArea kenarının stilini alır

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - 2D BarcodeArea kenarının stili
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


2D tanıma işaretçisinin rengini alır

**Returns:**
int - 1D tanıma işaretçisinin rengi
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


2D alan kenar çizgisinin genişliğini alır

**Returns:**
float - 2D alan kenar çizgisinin genişliği
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Tanıma alanının genişlik ve yükseklik oranını alır

**Returns:**
float - tanıma alanının genişlik ve yükseklik oranı
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
boolean - tanıma alanının görünürlüğü
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


barkod tarayıcı çerçevesinin boya rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Tanıma alanının maksimum yüksekliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxAreaHeight | float | tanıma alanının maksimum yüksekliği |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Tanıma alanının maksimum genişliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxAreaWidth | float | tanıma alanının maksimum genişliği |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


1D BarcodeArea satırının stilini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 1D BarcodeArea satırının stili |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


1D tanıma işaretçisinin rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oneDLineColor | int | 1D tanı işaretinin rengi |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


1D alan kenar çizgisinin genişliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oneDLineWidth | float | 1D alan kenar çizgisinin genişliği |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Barkod tanıma alanının boya rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionAreaColor | int | barkod tanıma alanının rengi. Renk şeffaf olmazsa, barkod tanıma alanı şeffaf olmayacaktır |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Tanıma alanının görünürlüğü |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Tanıma alanının ekranın üstünden ofsetini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| topOffset | float | ekranın üstünden tanıma alanı offseti |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


2D BarcodeArea satırının stilini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 2D BarcodeArea satırının stili |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Yuvarlatılmış köşe yarıçapını döndürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| twoDAreaCornerRadius | float | yuvarlatılmış köşe yarıçapı |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


2D BarcodeArea kenarının stilini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | 2D BarcodeArea kenarının stili |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


1D tanıma işaretçisinin rengini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| twoDLineColor | int | 1D tanı işaretinin rengi |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


2D alan kenar çizgisinin genişliğini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| twoDLineWidth | float | 2D alan kenar çizgisinin genişliği |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Tanıma alanının genişlik ve yükseklik oranını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| areaRatio | float | tanıma alanının genişlik ve yükseklik oranı |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

