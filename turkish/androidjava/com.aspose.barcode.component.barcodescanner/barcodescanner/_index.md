---
title: "BarcodeScanner"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "BarcodeScanner, Android cihaz kamerasından barkod tanıma ile ilgili işlevselliği içerir."
type: docs
weight: 12
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/barcodescanner/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeScanner
```

BarcodeScanner, Android cihaz kamerasından barkod tanıma ile ilgili işlevselliği içerir.

```
This sample shows how to use BarcodeScanner.
 
 // BarcodeScanner should be initialized in custom Activity in onCreate method,
 because BarcodeScanner must to initialize BarcodeScannerActivity in application
 BarcodeScanner scanner = new BarcodeScanner(getActivity());
 // Sets OnScanFinishedHandler that takes custom implementation of OnScannerRecognitionFinishedListener.
 // This OnScanFinishedHandler will be called after return from BarcodeScannerActivity
 scanner.setOnScanFinishedHandler(recognitionHandler -> {
                     AlertDialog.Builder dialog = new AlertDialog.Builder(requireContext());
                     dialog.setMessage(((ClientResultsListener)recognitionHandler).resultString);
                     dialog.create().show();
                 });
 // Initialize custom implementation of OnScannerRecognitionFinishedListener
 ClientResultsListener listener = new ClientResultsListener();
 // Launch BarcodeScannerActivity
 scanner.launchBarcodeScanner(listener);

 // Custom implementation of OnScannerRecognitionFinishedListener that process barcode recognition result
 on BarcodeScannerActivity side
 private class CustomResultsListener implements OnScannerRecognitionFinishedListener
 {
     public String resultString;

     public ClientResultsListener() {}

     protected ClientResultsListener(Parcel in) {
         resultString = in.readString();
     }
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BarcodeScanner(ComponentActivity parentActivity)](#BarcodeScanner-androidx.activity.ComponentActivity-) | BarcodeScanner sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPreferences()](#getPreferences--) |  |
| [hashCode()](#hashCode--) |  |
| [launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler)](#launchBarcodeScanner-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-) | Kamera görünümünü başlat ve tanıma sürecini yönet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback)](#setOnBarcodeScannerCompletedCallback-com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback-) | Tanıma tamamlandığında dinleyici |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScanner(ComponentActivity parentActivity) {#BarcodeScanner-androidx.activity.ComponentActivity-}
```
public BarcodeScanner(ComponentActivity parentActivity)
```


BarcodeScanner sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parentActivity | androidx.activity.ComponentActivity | BarcodeScanner'ın çağrıldığı aktivite. Üst aktivite görünümü oluşturulmadan önce başlatılmalıdır. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPreferences() {#getPreferences--}
```
public BarcodeScannerPreferences getPreferences()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences - Barkod tarayıcı tercihleri
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler) {#launchBarcodeScanner-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-}
```
public void launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler)
```


Kamera görünümünü başlat ve tanıma sürecini yönet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeRecognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable | Tanıma sonucunu işleyen soyut OnScannerRecognitionFinishedListener sınıfının özel örneği |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback) {#setOnBarcodeScannerCompletedCallback-com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback-}
```
public void setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback)
```


Tanıma tamamlandığında dinleyici

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| onBarcodeScannerCompletedCallback | com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback | dinleyici |

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

