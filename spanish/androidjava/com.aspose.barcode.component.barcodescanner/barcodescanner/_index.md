---
title: BarcodeScanner
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: BarcodeScanner contiene la funcionalidad relacionada con el reconocimiento de códigos de barras desde la cámara del dispositivo Android.
type: docs
weight: 12
url: /es/androidjava/com.aspose.barcode.component.barcodescanner/barcodescanner/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeScanner
```

BarcodeScanner contiene la funcionalidad relacionada con el reconocimiento de códigos de barras desde la cámara del dispositivo Android.

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
## Constructors

| Constructor | Descripción |
| --- | --- |
| [BarcodeScanner(ComponentActivity parentActivity)](#BarcodeScanner-androidx.activity.ComponentActivity-) | Inicializa una nueva instancia de la clase BarcodeScanner. |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPreferences()](#getPreferences--) |  |
| [hashCode()](#hashCode--) |  |
| [launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler)](#launchBarcodeScanner-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-) | Inicia la vista de la cámara y gestiona el proceso de reconocimiento |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback)](#setOnBarcodeScannerCompletedCallback-com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback-) | Listener de reconocimiento finalizado |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScanner(ComponentActivity parentActivity) {#BarcodeScanner-androidx.activity.ComponentActivity-}
```
public BarcodeScanner(ComponentActivity parentActivity)
```


Inicializa una nueva instancia de la clase BarcodeScanner.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parentActivity | androidx.activity.ComponentActivity | actividad desde la cual se llamó a BarcodeScanner. Debe inicializarse antes de que se cree la vista de la actividad principal |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
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
com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences - Preferencias del escáner de códigos de barras
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


Inicia la vista de la cámara y gestiona el proceso de reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeRecognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable | Instancia personalizada de la clase abstracta OnScannerRecognitionFinishedListener que procesa el resultado del reconocimiento |

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


Listener de reconocimiento finalizado

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| onBarcodeScannerCompletedCallback | com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback | escucha |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

