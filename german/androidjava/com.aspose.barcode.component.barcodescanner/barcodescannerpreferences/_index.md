---
title: "BarcodeScannerPreferences"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Die BarcodeScanner‑Einstellungen."
type: docs
weight: 16
url: /de/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

Die BarcodeScanner-Einstellungen. Enthält Parameter, die den Erkennungsprozess und die erkannten Daten beeinflussen. BarcodeScannerPreferences erweitert BarcodeRecognitionSettings, die Klasse BarcodeScannerPreferences enthält spezifische Elemente für die BarcodeScanner-API und implementiert das Parcelable-Interface, um Einstellungen zwischen der Client‑Aktivität und der BarcodeScannerActivity auszutauschen. BarcodeScannerPreferences funktionieren nur innerhalb der Client‑Anwendung über die BarcodeScannerActivity.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | Liest, ob die Anzeige‑rotation aktiviert ist. Standard ist false |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | Setzt, ob die Anzeige‑rotation aktiviert ist. Empfohlene Verwendung: false |
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
| Parameter | Typ | Beschreibung |
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


Liest, ob die Anzeige‑rotation aktiviert ist. Standard ist false

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


Setzt, ob die Anzeige‑rotation aktiviert ist. Empfohlene Verwendung: false

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

