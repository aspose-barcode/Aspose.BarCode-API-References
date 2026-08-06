---
title: BarcodeScannerPreferences
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Οι προτιμήσεις του BarcodeScanner.
type: docs
weight: 16
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

Οι προτιμήσεις του BarcodeScanner. Περιέχει παραμέτρους που επηρεάζουν τη διαδικασία αναγνώρισης και τα αναγνωρισμένα δεδομένα. Το BarcodeScannerPreferences επεκτείνει το BarcodeRecognitionSettings, η κλάση BarcodeScannerPreferences περιέχει ειδικά στοιχεία για το API του BarcodeScanner και υλοποιεί τη διεπαφή Parcelable για την ανταλλαγή προτιμήσεων μεταξύ της δραστηριότητας πελάτη και του BarcodeScannerActivity. Το BarcodeScannerPreferences λειτουργεί μόνο μέσα στην εφαρμογή πελάτη μέσω του BarcodeScannerActivity.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | Λαμβάνει την ενεργοποίηση περιστροφής της οθόνης. Η προεπιλογή είναι false |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | Ορίζει την ενεργοποίηση περιστροφής της οθόνης. Συνιστάται η χρήση false |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeScannerPreferences> CREATOR
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
### getBarcodeRecognitionSettings() {#getBarcodeRecognitionSettings--}
```
public BarcodeRecognitionSettings getBarcodeRecognitionSettings()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeRecognitionSettings
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRotationEnabled() {#isRotationEnabled--}
```
public boolean isRotationEnabled()
```


Λαμβάνει την ενεργοποίηση περιστροφής της οθόνης. Η προεπιλογή είναι false

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setRotationEnabled(boolean rotationEnabled) {#setRotationEnabled-boolean-}
```
public void setRotationEnabled(boolean rotationEnabled)
```


Ορίζει την ενεργοποίηση περιστροφής της οθόνης. Συνιστάται η χρήση false

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| rotationEnabled | boolean |  |

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

