---
title: RecognitionAreaSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 21
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | बारकोड स्कैनर फ्रेम का पेंट रंग प्राप्त करता है |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | पहचान क्षेत्र की अधिकतम ऊँचाई प्राप्त करता है |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | पहचान क्षेत्र की अधिकतम चौड़ाई प्राप्त करता है |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | 1D BarcodeArea लाइन की शैली प्राप्त करता है |
| [getOneDLineColor()](#getOneDLineColor--) | 1D पहचान मार्कर का रंग प्राप्त करता है |
| [getOneDLineWidth()](#getOneDLineWidth--) | 1D क्षेत्र बॉर्डर लाइन की चौड़ाई प्राप्त करता है |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | बारकोड पहचान क्षेत्र का पेंट रंग प्राप्त करता है |
| [getTopOffset()](#getTopOffset--) | स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफ़सेट प्रतिशत में प्राप्त करता है (TODO) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | 2D BarcodeArea लाइन की शैली प्राप्त करता है |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | गोल कोने की त्रिज्या लौटाता है |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | 2D BarcodeArea बॉर्डर की शैली प्राप्त करता है |
| [getTwoDLineColor()](#getTwoDLineColor--) | 2D पहचान मार्कर का रंग प्राप्त करता है |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | 2D क्षेत्र बॉर्डर लाइन की चौड़ाई प्राप्त करता है |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | बारकोड स्कैनर फ्रेम का पेंट रंग सेट करता है |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | पहचान क्षेत्र की अधिकतम ऊँचाई सेट करता है |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | पहचान क्षेत्र की अधिकतम चौड़ाई सेट करता है |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 1D बारकोडएरिया लाइन की शैली सेट करता है |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | 1D पहचान मार्कर का रंग सेट करता है |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | 1D क्षेत्र सीमा लाइन की चौड़ाई सेट करता है |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | बारकोड पहचान क्षेत्र का पेंट रंग सेट करता है |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफसेट सेट करता है |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | 2D बारकोडएरिया लाइन की शैली सेट करता है |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | गोल कोने की त्रिज्या लौटाता है |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | 2D बारकोडएरिया बॉर्डर की शैली सेट करता है |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | 1D पहचान मार्कर का रंग सेट करता है |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | 2D क्षेत्र सीमा लाइन की चौड़ाई सेट करता है |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात सेट करता है |
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
| Parameter | Type | विवरण |
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


बारकोड स्कैनर फ्रेम का पेंट रंग प्राप्त करता है

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


पहचान क्षेत्र की अधिकतम ऊँचाई प्राप्त करता है

**Returns:**
float - पहचान क्षेत्र की अधिकतम ऊँचाई
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


पहचान क्षेत्र की अधिकतम चौड़ाई प्राप्त करता है

**Returns:**
float - पहचान क्षेत्र की अधिकतम चौड़ाई
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


1D BarcodeArea लाइन की शैली प्राप्त करता है

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


1D पहचान मार्कर का रंग प्राप्त करता है

**Returns:**
int - 1D पहचान मार्कर का रंग
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


1D क्षेत्र बॉर्डर लाइन की चौड़ाई प्राप्त करता है

**Returns:**
float - 1D क्षेत्र सीमा लाइन की चौड़ाई
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


बारकोड पहचान क्षेत्र का पेंट रंग प्राप्त करता है

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफ़सेट प्रतिशत में प्राप्त करता है (TODO)

**Returns:**
float - स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफसेट
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


2D BarcodeArea लाइन की शैली प्राप्त करता है

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


गोल कोने की त्रिज्या लौटाता है

**Returns:**
float - गोल कोने की त्रिज्या
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


2D BarcodeArea बॉर्डर की शैली प्राप्त करता है

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - 2D बारकोडएरिया बॉर्डर की शैली
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


2D पहचान मार्कर का रंग प्राप्त करता है

**Returns:**
int - 1D पहचान मार्कर का रंग
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


2D क्षेत्र बॉर्डर लाइन की चौड़ाई प्राप्त करता है

**Returns:**
float - 2D क्षेत्र सीमा लाइन की चौड़ाई
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात प्राप्त करता है

**Returns:**
float - पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात
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
boolean - पहचान क्षेत्र की दृश्यता
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


बारकोड स्कैनर फ्रेम का पेंट रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


पहचान क्षेत्र की अधिकतम ऊँचाई सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| maxAreaHeight | float | पहचान क्षेत्र की अधिकतम ऊँचाई |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


पहचान क्षेत्र की अधिकतम चौड़ाई सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| maxAreaWidth | float | पहचान क्षेत्र की अधिकतम चौड़ाई |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


1D बारकोडएरिया लाइन की शैली सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 1D बारकोडएरिया लाइन की शैली |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


1D पहचान मार्कर का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| oneDLineColor | int | 1D पहचान मार्कर का रंग |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


1D क्षेत्र सीमा लाइन की चौड़ाई सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| oneDLineWidth | float | 1D क्षेत्र सीमा रेखा की चौड़ाई |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


बारकोड पहचान क्षेत्र का पेंट रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionAreaColor | int | बारकोड पहचान क्षेत्र का रंग। यदि रंग पारदर्शी नहीं होगा, तो बारकोड पहचान क्षेत्र भी पारदर्शी नहीं रहेगा |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | पहचान क्षेत्र की दृश्यता |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफसेट सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| topOffset | float | स्क्रीन के शीर्ष से पहचान क्षेत्र का ऑफ़सेट |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


2D बारकोडएरिया लाइन की शैली सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | 2D बारकोडएरिया लाइन की शैली |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


गोल कोने की त्रिज्या लौटाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| twoDAreaCornerRadius | float | गोल कोने की त्रिज्या |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


2D बारकोडएरिया बॉर्डर की शैली सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | 2D बारकोडएरिया बॉर्डर की शैली |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


1D पहचान मार्कर का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| twoDLineColor | int | 1D पहचान मार्कर का रंग |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


2D क्षेत्र सीमा लाइन की चौड़ाई सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| twoDLineWidth | float | 2D क्षेत्र सीमा रेखा की चौड़ाई |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| areaRatio | float | पहचान क्षेत्र की चौड़ाई और ऊँचाई के बीच अनुपात |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

