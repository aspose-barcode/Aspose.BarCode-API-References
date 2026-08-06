---
title: BarcodeRecognitionSettings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: BarcodeRecognitionSettings يحتوي على API لتخصيص BarcodeRecognitionFragment وإعدادات التعرف على الباركود مع إضافة RecognitionResultsHandler. يجب استدعاؤه قبل بدء عملية التعرف في BarcodeScannerFragment.
type: docs
weight: 11
url: /ar/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings يحتوي على API لتخصيص BarcodeRecognitionFragment وإعدادات التعرف على الباركود، إضافة RecognitionResultsHandler يجب استدعاؤها قبل بدء عملية التعرف في BarcodeScannerFragment. //TODO مناقشة طريقة applyChanges أو importSettings
## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | داخلي |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | معلمات فك ترميز BarCode الرئيسية. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | غير مُنفّذ |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | يستورد خصائص BarCode من تدفق xml المحدد ويطبقها على نسخة BarCodeReader الحالية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | يضبط نوع فك الترميز للتعرف. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | يضبط مصفوفة النوع SingleDecodeType للتعرف. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | يضبط تنفيذًا مخصصًا لـ OnRecognitionFinishedListener. سيتم استدعاء OnRecognitionFinishedListener المخصص بعد انتهاء عملية التعرف في BarcodeScannerFragment. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. |
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
| Parameter | Type | الوصف |
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


داخلي

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


معلمات فك ترميز BarCode الرئيسية. تحتوي على معلمات تؤثر على البيانات المُعترف بها.

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


غير مُنفّذ

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


يستورد خصائص BarCode من تدفق xml المحدد ويطبقها على نسخة BarCodeReader الحالية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | تدفق xml للتحميل |

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


يضبط نوع فك الترميز للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes().

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | نوع الباركود الذي سيتم قراءته. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


يضبط مصفوفة النوع SingleDecodeType للتعرف. يجب استدعاؤها قبل بدء عملية التعرف في BarcodeScannerFragment.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | مصفوفة النوع SingleDecodeType للقراءة. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


يضبط تنفيذًا مخصصًا لـ OnRecognitionFinishedListener. سيتم استدعاء OnRecognitionFinishedListener المخصص بعد انتهاء عملية التعرف في BarcodeScannerFragment.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة باستخدام الإعدادات المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات بشكل منفصل يدويًا. القيمة الافتراضية لـ QualitySettings هي NormalQuality.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | لتكوين جودة وسرعة التعرف. |

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

