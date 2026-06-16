---
title: BarcodeSvmDetectorSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: बारकोड डिटेक्टर सेटिंग्स।
type: docs
weight: 22
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeSvmDetectorSettings implements Parcelable
```

बारकोड डिटेक्टर सेटिंग्स।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHighPerformance()](#getHighPerformance--) | उच्च प्रदर्शन पहचान प्रीसेट। |
| [getHighQuality()](#getHighQuality--) | उच्च गुणवत्ता पहचान प्रीसेट। |
| [getMaxQuality()](#getMaxQuality--) | अधिकतम गुणवत्ता पहचान प्रीसेट। |
| [getMedianFilterWindowSize()](#getMedianFilterWindowSize--) | मीडियन स्मूदिंग के लिए विंडो आकार। |
| [getNormalQuality()](#getNormalQuality--) | सामान्य गुणवत्ता पहचान प्रीसेट। |
| [getRegionLikelihoodThresholdPercent()](#getRegionLikelihoodThresholdPercent--) | बारकोड्स शामिल कर सकते हैं ऐसे पहचाने गए क्षेत्रों के लिए थ्रेशोल्ड सेट करता है। |
| [getScanWindowSizes()](#getScanWindowSizes--) | पिक्सेल में स्कैन विंडो आकार। |
| [getSimilarityCoef()](#getSimilarityCoef--) | समानता गुणांक इस बात पर निर्भर करता है कि बारकोड्स कितने समान हैं। |
| [getSkipDiagonalSearch()](#getSkipDiagonalSearch--) | डिटेक्टर को विकर्ण बारकोड्स की खोज को छोड़ने की अनुमति देता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMedianFilterWindowSize(int value)](#setMedianFilterWindowSize-int-) | मीडियन स्मूदिंग के लिए विंडो आकार। |
| [setRegionLikelihoodThresholdPercent(float value)](#setRegionLikelihoodThresholdPercent-float-) | बारकोड्स शामिल कर सकते हैं ऐसे पहचाने गए क्षेत्रों के लिए थ्रेशोल्ड सेट करता है। |
| [setScanWindowSizes(List<Integer> value)](#setScanWindowSizes-java.util.List-java.lang.Integer--) | पिक्सेल में स्कैन विंडो आकार। |
| [setSimilarityCoef(float value)](#setSimilarityCoef-float-) | समानता गुणांक इस बात पर निर्भर करता है कि बारकोड्स कितने समान हैं। |
| [setSkipDiagonalSearch(boolean value)](#setSkipDiagonalSearch-boolean-) | डिटेक्टर को विकर्ण बारकोड्स की खोज को छोड़ने की अनुमति देता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeSvmDetectorSettings> CREATOR
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
### getHighPerformance() {#getHighPerformance--}
```
public static BarcodeSvmDetectorSettings getHighPerformance()
```


उच्च प्रदर्शन पहचान प्रीसेट।

QualitySettings.PresetType.HighPerformance के लिए डिफ़ॉल्ट।

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getHighQuality() {#getHighQuality--}
```
public static BarcodeSvmDetectorSettings getHighQuality()
```


उच्च गुणवत्ता पहचान प्रीसेट।

QualitySettings.PresetType.HighQualityDetection और QualitySettings.PresetType.HighQuality के लिए डिफ़ॉल्ट।

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMaxQuality() {#getMaxQuality--}
```
public static BarcodeSvmDetectorSettings getMaxQuality()
```


अधिकतम गुणवत्ता पहचान प्रीसेट।

QualitySettings.PresetType.MaxQualityDetection और QualitySettings.PresetType.MaxBarCodes के लिए डिफ़ॉल्ट।

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getMedianFilterWindowSize() {#getMedianFilterWindowSize--}
```
public int getMedianFilterWindowSize()
```


मीडियन स्मूदिंग के लिए विंडो आकार।

आम मान 3 या 4 होते हैं। 0 का मतलब कोई मीडियन स्मूदिंग नहीं। डिफ़ॉल्ट मान 0 है। मीडियन फ़िल्टर विंडो आकार [0, 10] के बीच होना चाहिए।

**Returns:**
int
### getNormalQuality() {#getNormalQuality--}
```
public static BarcodeSvmDetectorSettings getNormalQuality()
```


सामान्य गुणवत्ता पहचान प्रीसेट।

QualitySettings.PresetType.NormalQuality के लिए डिफ़ॉल्ट।

**Returns:**
com.aspose.barcode.barcoderecognition.BarcodeSvmDetectorSettings
### getRegionLikelihoodThresholdPercent() {#getRegionLikelihoodThresholdPercent--}
```
public float getRegionLikelihoodThresholdPercent()
```


बारकोड्स शामिल कर सकते हैं ऐसे पहचाने गए क्षेत्रों के लिए थ्रेशोल्ड सेट करता है।

मान 0.7 का अर्थ है कि संभावित क्षेत्रों के नीचे के 70% को फ़िल्टर किया जाता है और आगे प्रोसेस नहीं किया जाता। क्षेत्र संभावना थ्रेशोल्ड [0.05, 0.9] के बीच होना चाहिए। कम बारकोड वाले स्पष्ट इमेज के लिए उच्च मान उपयोग करें। कई बारकोड वाले या शोरयुक्त इमेज के लिए कम मान उपयोग करें। कम मान पहचान समय को बढ़ा सकता है।

**Returns:**
float
### getScanWindowSizes() {#getScanWindowSizes--}
```
public List<Integer> getScanWindowSizes()
```


पिक्सेल में स्कैन विंडो आकार।

अनुमत आकार 10, 15, 20, 25, 30 हैं। छोटे विंडो आकार के साथ स्कैनिंग में अधिक समय लगता है और अधिक सटीकता मिलती है, लेकिन बहुत बड़े बारकोड्स का पता लगाने में विफल हो सकता है। कई विंडो आकारों को मिलाकर पहचान गुणवत्ता में सुधार किया जा सकता है।

**Returns:**
java.util.List<java.lang.Integer>
### getSimilarityCoef() {#getSimilarityCoef--}
```
public float getSimilarityCoef()
```


समानता गुणांक इस बात पर निर्भर करता है कि बारकोड्स कितने समान हैं।

स्पष्ट बारकोड्स के लिए उच्च मान उपयोग करें। आंशिक रूप से क्षतिग्रस्त या असमान रूप से प्रकाशित बारकोड्स का पता लगाने के लिए कम मान उपयोग करें। समानता गुणांक [0.5, 0.9] के बीच होना चाहिए।

**Returns:**
float
### getSkipDiagonalSearch() {#getSkipDiagonalSearch--}
```
public boolean getSkipDiagonalSearch()
```


डिटेक्टर को विकर्ण बारकोड्स की खोज को छोड़ने की अनुमति देता है।

इसे false सेट करने से पहचान समय बढ़ेगा लेकिन उन विकर्ण बारकोड्स को खोजने की अनुमति देगा जो अन्यथा छूट सकते हैं। विकर्ण खोज को सक्षम करने से पहचान समय और बढ़ जाता है।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMedianFilterWindowSize(int value) {#setMedianFilterWindowSize-int-}
```
public void setMedianFilterWindowSize(int value)
```


मीडियन स्मूदिंग के लिए विंडो आकार।

आम मान 3 या 4 होते हैं। 0 का मतलब कोई मीडियन स्मूदिंग नहीं। डिफ़ॉल्ट मान 0 है। मीडियन फ़िल्टर विंडो आकार [0, 10] के बीच होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRegionLikelihoodThresholdPercent(float value) {#setRegionLikelihoodThresholdPercent-float-}
```
public void setRegionLikelihoodThresholdPercent(float value)
```


बारकोड्स शामिल कर सकते हैं ऐसे पहचाने गए क्षेत्रों के लिए थ्रेशोल्ड सेट करता है।

मान 0.7 का अर्थ है कि संभावित क्षेत्रों के नीचे के 70% को फ़िल्टर किया जाता है और आगे प्रोसेस नहीं किया जाता। क्षेत्र संभावना थ्रेशोल्ड [0.05, 0.9] के बीच होना चाहिए। कम बारकोड वाले स्पष्ट इमेज के लिए उच्च मान उपयोग करें। कई बारकोड वाले या शोरयुक्त इमेज के लिए कम मान उपयोग करें। कम मान पहचान समय को बढ़ा सकता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setScanWindowSizes(List<Integer> value) {#setScanWindowSizes-java.util.List-java.lang.Integer--}
```
public void setScanWindowSizes(List<Integer> value)
```


पिक्सेल में स्कैन विंडो आकार।

अनुमत आकार 10, 15, 20, 25, 30 हैं। छोटे विंडो आकार के साथ स्कैनिंग में अधिक समय लगता है और अधिक सटीकता मिलती है, लेकिन बहुत बड़े बारकोड्स का पता लगाने में विफल हो सकता है। कई विंडो आकारों को मिलाकर पहचान गुणवत्ता में सुधार किया जा सकता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.util.List<java.lang.Integer> |  |

### setSimilarityCoef(float value) {#setSimilarityCoef-float-}
```
public void setSimilarityCoef(float value)
```


समानता गुणांक इस बात पर निर्भर करता है कि बारकोड्स कितने समान हैं।

स्पष्ट बारकोड्स के लिए उच्च मान उपयोग करें। आंशिक रूप से क्षतिग्रस्त या असमान रूप से प्रकाशित बारकोड्स का पता लगाने के लिए कम मान उपयोग करें। समानता गुणांक [0.5, 0.9] के बीच होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setSkipDiagonalSearch(boolean value) {#setSkipDiagonalSearch-boolean-}
```
public void setSkipDiagonalSearch(boolean value)
```


डिटेक्टर को विकर्ण बारकोड्स की खोज को छोड़ने की अनुमति देता है।

इसे false सेट करने से पहचान समय बढ़ेगा लेकिन उन विकर्ण बारकोड्स को खोजने की अनुमति देगा जो अन्यथा छूट सकते हैं। विकर्ण खोज को सक्षम करने से पहचान समय और बढ़ जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

