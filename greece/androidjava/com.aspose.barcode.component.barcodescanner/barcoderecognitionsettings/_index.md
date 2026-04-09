---
title: BarcodeRecognitionSettings
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Το BarcodeRecognitionSettings περιέχει το API για την προσαρμογή του BarcodeRecognitionFragment και των ρυθμίσεων αναγνώρισης Barcode με προσθήκη του RecognitionResultsHandler. Πρέπει να κληθεί πριν ξεκινήσει η διαδικασία αναγνώρισης στο BarcodeScannerFragment.
type: docs
weight: 11
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class BarcodeRecognitionSettings implements Parcelable
```

Το BarcodeRecognitionSettings περιέχει το API για προσαρμογή του BarcodeRecognitionFragment και των ρυθμίσεων αναγνώρισης Barcode, η προσθήκη του RecognitionResultsHandler πρέπει να κληθεί πριν από την έναρξη της διαδικασίας αναγνώρισης στο BarcodeScannerFragment. //TODO συζήτηση για τη μέθοδο applyChanges ή importSettings
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarCodeReadType()](#getBarCodeReadType--) |  |
| [getBarcodeReaderSettings()](#getBarcodeReaderSettings--) | εσωτερικό |
| [getBarcodeScannerFragmentSettings()](#getBarcodeScannerFragmentSettings--) |  |
| [getBarcodeSettings()](#getBarcodeSettings--) | Οι κύριες παράμετροι αποκωδικοποίησης BarCode. |
| [getClass()](#getClass--) |  |
| [getQualitySettings()](#getQualitySettings--) | Δεν έχει υλοποιηθεί |
| [hashCode()](#hashCode--) |  |
| [importSettingsFromXml(InputStream barcodeReaderExportedToXml)](#importSettingsFromXml-java.io.InputStream-) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και τις εφαρμόζει στην τρέχουσα παρουσία BarCodeReader. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Ορίζει τον τύπο αποκωδικοποίησης για την αναγνώριση. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Ορίζει έναν πίνακα τύπου SingleDecodeType για την αναγνώριση. |
| [setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)](#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-) | Ορίζει προσαρμοσμένη υλοποίηση του OnRecognitionFinishedListener. Ο προσαρμοσμένος OnRecognitionFinishedListener θα κληθεί μετά το τέλος της διαδικασίας αναγνώρισης στο BarcodeScannerFragment. |
| [setQualitySettings(QualitySettings qualitySettings)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | Οι QualitySettings επιτρέπουν τη χειροκίνητη ρύθμιση της ποιότητας και της ταχύτητας της αναγνώρισης. |
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
| Parameter | Type | Περιγραφή |
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


εσωτερικό

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


Οι κύριες παράμετροι αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα.

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


Δεν έχει υλοποιηθεί

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


Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και τις εφαρμόζει στην τρέχουσα παρουσία BarCodeReader.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| barcodeReaderExportedToXml | java.io.InputStream | Το xml-stream για φόρτωση |

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


Ορίζει τον τύπο αποκωδικοποίησης για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Ο τύπος του barcode προς ανάγνωση. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Ορίζει έναν πίνακα τύπου SingleDecodeType για την αναγνώριση. Πρέπει να κληθεί πριν από την έναρξη της διαδικασίας αναγνώρισης στο BarcodeScannerFragment.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ο πίνακας τύπου SingleDecodeType για ανάγνωση. |

### setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler) {#setBarcodeRecognitionResultHandler-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler-}
```
public void setBarcodeRecognitionResultHandler(BarcodeRecognitionResultsHandler recognitionResultsHandler)
```


Ορίζει προσαρμοσμένη υλοποίηση του OnRecognitionFinishedListener. Ο προσαρμοσμένος OnRecognitionFinishedListener θα κληθεί μετά το τέλος της διαδικασίας αναγνώρισης στο BarcodeScannerFragment.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| recognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandler |  |

### setQualitySettings(QualitySettings qualitySettings) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings qualitySettings)
```


Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings χρησιμοποιώντας ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| qualitySettings | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) | για τη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

