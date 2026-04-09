---
title: BarcodeRecognitionSettings
second_title: Aspose.BarCode for Android via Java API-referens
description: BarcodeRecognitionSettings innehåller API:et för anpassning av BarcodeRecognitionFragment och inställningar för Barcode-igenkänning samt tillägg av RecognitionResultsHandler. Måste anropas innan igenkänningsprocessen startas i BarcodeScannerFragment.
type: docs
weight: 11
url: /sv/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings innehåller API:t för anpassning av BarcodeRecognitionFragment och inställningar för streckkodigenkänning, tillägg av RecognitionResultsHandler måste anropas innan start av igenkänningsprocessen i BarcodeScannerFragment. //TODO discuss method applyChanges or importSettings
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | intern |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | De huvudsakliga BarCode‑avkodningsparametrarna. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | Inte implementerad |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | Importerar BarCode-egenskaper från den angivna xml-strömmen och tillämpar dem på den aktuella BarCodeReader-instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Ställer in avkodningstyp för igenkänning. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Ställer in  SingleDecodeType  typ‑array för igenkänning. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | Ställer in anpassad implementation av OnRecognitionFinishedListener. Anpassad OnRecognitionFinishedListener kommer att anropas efter att igenkänningsprocessen i BarcodeScannerFragment är klar. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings tillåter att konfigurera igenkänningskvalitet och hastighet manuellt. |
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
| Parameter | Type | Beskrivning |
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


intern

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


De viktigaste BarCode-avkodningsparametrarna. Innehåller parametrar som påverkar den igenkända datan.

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


Inte implementerad

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


Importerar BarCode-egenskaper från den angivna xml-strömmen och tillämpar dem på den aktuella BarCodeReader-instansen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | Xml‑strömmen för inläsning |

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


Ställer in avkodningstyp för igenkänning. Måste anropas innan metoden ReadBarCodes().

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Typen av streckkod att läsa. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Ställer in  SingleDecodeType  typ‑array för igenkänning. Måste anropas innan start av igenkänningsprocessen i BarcodeScannerFragment.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Den  SingleDecodeType  typ‑arrayen att läsa. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


Ställer in anpassad implementation av OnRecognitionFinishedListener. Anpassad OnRecognitionFinishedListener kommer att anropas efter att igenkänningsprocessen i BarcodeScannerFragment är klar.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | för att konfigurera igenkänningskvalitet och hastighet. |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

