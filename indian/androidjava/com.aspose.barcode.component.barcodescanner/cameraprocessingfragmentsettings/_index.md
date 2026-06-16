---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: CameraProcessingFragment के लिए सेटिंग्स
type: docs
weight: 20
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

CameraProcessingFragment के लिए सेटिंग्स
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | कैमरा उपयोग का मोड प्राप्त करता है। |
| [getCameraResolution()](#getCameraResolution--) | वर्तमान कैमरा रिज़ॉल्यूशन प्राप्त करता है। डिफ़ॉल्ट न्यूनतम रिज़ॉल्यूशन है। |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | PreferencesButtonContent का ContentDescriptionText प्राप्त करता है। |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | पहचान क्षेत्र मार्कर से संबंधित सेटिंग प्राप्त करता है। |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | RecognitionButton का ContentDescriptionText प्राप्त करता है। |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | RecognizeButton का आकार प्राप्त करता है। |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | PreferencesButton का आकार प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | यदि फ्लैश सक्षम है तो true लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO: प्रॉपर्टीज़ में जोड़ें? कैमरा उपयोग का मोड सेट करता है। |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | कैमरा रिज़ॉल्यूशन सेट करता है। डिफ़ॉल्ट न्यूनतम रिज़ॉल्यूशन है। |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | फ्लैश लाइट सक्षम करता है। केवल CameraMode.PHOTO के साथ उपयुक्त। डिफ़ॉल्ट true है। |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | PreferencesButtonContent का ContentDescriptionText सेट करता है। |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | पहचान क्षेत्र मार्कर से संबंधित सेटिंग सेट करता है। |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | RecognitionButton का ContentDescriptionText सेट करता है। |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | RecognizeButton का आकार सेट करता है। |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | PreferencesButton का आकार सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel parcel, int i)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<CameraProcessingFragmentSettings> CREATOR
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
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


कैमरा उपयोग का मोड प्राप्त करता है। वर्तमान में दो मोड समर्थित हैं = PHOTO और SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


वर्तमान कैमरा रिज़ॉल्यूशन प्राप्त करता है। डिफ़ॉल्ट न्यूनतम रिज़ॉल्यूशन है।

**Returns:**
android.util.Size -
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPreferencesButtonContentDescriptionText() {#getPreferencesButtonContentDescriptionText--}
```
public String getPreferencesButtonContentDescriptionText()
```


PreferencesButtonContent का ContentDescriptionText प्राप्त करता है।

**Returns:**
java.lang.String - PreferencesButtonContent का ContentDescriptionText
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


पहचान क्षेत्र मार्कर से संबंधित सेटिंग प्राप्त करता है।

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


RecognitionButton का ContentDescriptionText प्राप्त करता है।

**Returns:**
java.lang.String - RecognitionButton का ContentDescriptionText
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


RecognizeButton का आकार प्राप्त करता है।

**Returns:**
int - RecognizeButton का आकार
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


PreferencesButton का आकार प्राप्त करता है।

**Returns:**
int - PreferencesButton का आकार
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFlashEnabled() {#isFlashEnabled--}
```
public boolean isFlashEnabled()
```


यदि फ्लैश सक्षम है तो true लौटाता है। केवल CameraMode.PHOTO के साथ उपयुक्त है। डिफ़ॉल्ट true है

**Returns:**
boolean -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCameraProcessingMode(CameraMode cameraProcessingMode) {#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-}
```
public void setCameraProcessingMode(CameraMode cameraProcessingMode)
```


TODO प्रॉपर्टीज़ में जोड़ें? कैमरा उपयोग का मोड सेट करता है। वर्तमान में दो मोड समर्थित हैं = PHOTO और SNAPSHOT

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


कैमरा रिज़ॉल्यूशन सेट करता है। डिफ़ॉल्ट न्यूनतम रिज़ॉल्यूशन है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


फ्लैश लाइट सक्षम करता है। केवल CameraMode.PHOTO के साथ उपयुक्त। डिफ़ॉल्ट true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


PreferencesButtonContent का ContentDescriptionText सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | PreferencesButtonContent का ContentDescriptionText |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


पहचान क्षेत्र मार्कर से संबंधित सेटिंग सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


RecognitionButton का ContentDescriptionText सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | RecognitionButton का ContentDescriptionText |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


RecognizeButton का आकार सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton का आकार |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


PreferencesButton का आकार सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | PreferencesButton का आकार |

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

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

