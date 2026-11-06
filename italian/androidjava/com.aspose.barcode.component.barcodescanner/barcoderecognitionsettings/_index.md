---
title: "BarcodeRecognitionSettings"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "BarcodeRecognitionSettings contiene l'API per la personalizzazione di BarcodeRecognitionFragment e le impostazioni di riconoscimento dei codici a barre, aggiungendo RecognitionResultsHandler. Deve essere chiamato prima dell'avvio del processo di riconoscimento in BarcodeScannerFragment."
type: docs
weight: 11
url: /it/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

BarcodeRecognitionSettings contiene l'API per la personalizzazione di BarcodeRecognitionFragment e le impostazioni di riconoscimento dei codici a barre, aggiungendo RecognitionResultsHandler. Deve essere chiamato prima dell'avvio del processo di riconoscimento in BarcodeScannerFragment. //TODO discuti il metodo applyChanges o importSettings
## Campi

| Campo | Descrizione |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | interno |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | I principali parametri di decodifica del BarCode. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | Non implementato |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | Importa le proprietà BarCode dallo stream XML specificato e le applica all'istanza corrente di BarCodeReader. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Imposta il tipo di decodifica per il riconoscimento. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Imposta l'array di tipo  SingleDecodeType  per il riconoscimento. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | Imposta l'implementazione personalizzata di OnRecognitionFinishedListener. Il Custom OnRecognitionFinishedListener verrà chiamato al termine del processo di riconoscimento in BarcodeScannerFragment. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. |
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
| Parametro | Tipo | Descrizione |
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


interno

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


I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti.

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


Non implementato

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


Importa le proprietà BarCode dallo stream XML specificato e le applica all'istanza corrente di BarCodeReader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | Lo stream XML per il caricamento |

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


Imposta il tipo di decodifica per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di codice a barre da leggere. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Imposta l'array di tipo  SingleDecodeType  per il riconoscimento. Deve essere chiamato prima dell'avvio del processo di riconoscimento in BarcodeScannerFragment.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | L'array di tipo  SingleDecodeType  da leggere. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


Imposta l'implementazione personalizzata di OnRecognitionFinishedListener. Il Custom OnRecognitionFinishedListener verrà chiamato al termine del processo di riconoscimento in BarcodeScannerFragment.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le singole opzioni. Il valore predefinito di QualitySettings è NormalQuality.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | per configurare la qualità e la velocità del riconoscimento. |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

