---
title: "BarcodeRecognitionSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "BarcodeRecognitionSettings, BarcodeRecognitionFragment'i özelleştirmek ve Barkod tanıma ayarlarını eklemek için API içerir; RecognitionResultsHandler eklenmesi BarcodeScannerFragment içinde tanıma süreci başlatılmadan önce çağrılmalıdır."
type: docs
weight: 11
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings, BarcodeRecognitionFragment'i özelleştirmek ve Barkod tanıma ayarlarını eklemek için API içerir; RecognitionResultsHandler eklenmesi BarcodeScannerFragment içinde tanıma süreci başlatılmadan önce çağrılmalıdır. //TODO discuss method applyChanges or importSettings
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | dahili |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | Ana BarCode kod çözme parametreleri. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | Uygulanmadı |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Tanıma için kod çözme türünü ayarlar. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Tanıma için  SingleDecodeType  tipinde dizi ayarlar. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | OnRecognitionFinishedListener için özel uygulamayı ayarlar. Özel OnRecognitionFinishedListener, BarcodeScannerFragment içinde tanıma işlemi tamamlandıktan sonra çağrılacaktır. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir. |
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
| Parametre | Tür | Açıklama |
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


dahili

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


Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreleri içerir.

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


Uygulanmadı

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


Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | Yükleme için xml akışı |

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


Tanıma için kod çözme türünü ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Okunacak barkodun türü. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Tanıma için  SingleDecodeType  tipinde dizi ayarlar. BarcodeScannerFragment içinde tanıma süreci başlamadan önce çağrılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Okunacak  SingleDecodeType  tipindeki dizi. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


OnRecognitionFinishedListener için özel uygulamayı ayarlar. Özel OnRecognitionFinishedListener, BarcodeScannerFragment içinde tanıma işlemi tamamlandıktan sonra çağrılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i yerleşik ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | tanıma kalitesini ve hızını yapılandırmak için. |

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

