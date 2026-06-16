---
title: BarcodeRecognitionSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: BarcodeRecognitionSettings में API है जो BarcodeRecognitionFragment और बारकोड पहचान सेटिंग्स को कस्टमाइज़ करने के लिए RecognitionResultsHandler जोड़ता है। इसे BarcodeScannerFragment में पहचान प्रक्रिया शुरू करने से पहले कॉल किया जाना चाहिए।
type: docs
weight: 11
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings में BarcodeRecognitionFragment और Barcode मान्यता सेटिंग्स को अनुकूलित करने के लिए API शामिल है, RecognitionResultsHandler को जोड़ना BarcodeScannerFragment में मान्यता प्रक्रिया शुरू करने से पहले बुलाया जाना चाहिए। //TODO discuss method applyChanges or importSettings
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | आंतरिक |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | मुख्य BarCode डिकोडिंग पैरामीटर। |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | लागू नहीं किया गया |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | निर्दिष्ट xml-stream से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | मान्यता के लिए डिकोड प्रकार सेट करता है। |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | मान्यता के लिए SingleDecodeType प्रकार की एरे सेट करता है। |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | OnRecognitionFinishedListener की कस्टम कार्यान्वयन सेट करता है। कस्टम OnRecognitionFinishedListener BarcodeScannerFragment में मान्यता प्रक्रिया समाप्त होने के बाद बुलाया जाएगा। |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings allows to configure recognition quality and speed manually. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeRecognitionSettings> CREATOR
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
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```




**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeReaderSettings() {#getBarcodeReaderSettings--}
```
public InputStream getBarcodeReaderSettings()
```


आंतरिक

**Returns:**
java.io.InputStream -
### getBarcodeScannerFragmentSettings() {#getBarcodeScannerFragmentSettings--}
```
public BarcodeScannerFragmentSettings getBarcodeScannerFragmentSettings()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeScannerFragmentSettings
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


मुख्य BarCode डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं।

**Returns:**
[BarcodeSettings](../../com.aspose.barcode.barcoderecognition/barcodesettings) - The main BarCode decoding parameters
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQualitySettings() {#getQualitySettings--}
```
public QualitySettings getQualitySettings()
```


लागू नहीं किया गया

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) - quality settings
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettingsFromXml(InputStream barcodeReaderExportedToXml) {#importSettingsFromXml-java.io.InputStream-}
```
public void importSettingsFromXml(InputStream barcodeReaderExportedToXml)
```


निर्दिष्ट xml-stream से BarCode गुण आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | लोड करने के लिए xml-stream |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


मान्यता के लिए डिकोड प्रकार सेट करता है। इसे ReadBarCodes() मेथड से पहले बुलाया जाना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | पढ़ने के लिए बारकोड का प्रकार। |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


मान्यता के लिए SingleDecodeType प्रकार की एरे सेट करता है। इसे BarcodeScannerFragment में मान्यता प्रक्रिया शुरू करने से पहले बुलाया जाना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | पढ़ने के लिए SingleDecodeType प्रकार की एरे। |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


OnRecognitionFinishedListener की कस्टम कार्यान्वयन सेट करता है। कस्टम OnRecognitionFinishedListener BarcodeScannerFragment में मान्यता प्रक्रिया समाप्त होने के बाद बुलाया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings आपको मान्यता की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | मान्यता की गुणवत्ता और गति को कॉन्फ़िगर करने के लिए। |

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

