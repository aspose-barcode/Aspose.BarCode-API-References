---
title: "BarcodeScannerPreferences"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "BarcodeScanner tercihleri."
type: docs
weight: 16
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

BarcodeScannerPreferences, Barcode tarayıcı tercihlerini temsil eder. Tanıma süreci ve tanınan veriler üzerinde etkisi olan parametreleri içerir. BarcodeScannerPreferences, BarcodeRecognitionSettings sınıfını genişletir, BarcodeScannerPreferences sınıfı BarcodeScanner API'sine özgü özellikler içerir ve tercihleri istemci aktivitesi ile BarcodeScannerActivity arasında değiştirmek için Parcelable arayüzünü uygular. BarcodeScannerPreferences yalnızca istemci uygulaması içinde BarcodeScannerActivity aracılığıyla çalışır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | Ekran döndürme etkinleştirme durumunu alır. Varsayılan false'tur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | Ekran döndürme etkinleştirme durumunu ayarlar. Önerilen kullanım false'tur. |
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
| Parametre | Tür | Açıklama |
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


Ekran döndürme etkinleştirme durumunu alır. Varsayılan false'tur.

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


Ekran döndürme etkinleştirme durumunu ayarlar. Önerilen kullanım false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
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

