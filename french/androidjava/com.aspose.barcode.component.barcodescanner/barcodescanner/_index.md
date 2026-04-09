---
title: BarcodeScanner
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: BarcodeScanner contient les fonctionnalités liées à la reconnaissance de codes-barres à partir de la caméra d'un appareil Android.
type: docs
weight: 12
url: /fr/androidjava/com.aspose.barcode.component.barcodescanner/barcodescanner/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeScanner
```

BarcodeScanner contient les fonctionnalités liées à la reconnaissance de codes-barres à partir de la caméra d'un appareil Android.

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeScanner(ComponentActivity parentActivity)](#BarcodeScanner-androidx.activity.ComponentActivity-) | Initialise une nouvelle instance de la classe BarcodeScanner. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPreferences()](#getPreferences--) |  |
| [hashCode()](#hashCode--) |  |
| [launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler)](#launchBarcodeScanner-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-) | Lance la vue de la caméra et gère le processus de reconnaissance |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback)](#setOnBarcodeScannerCompletedCallback-com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback-) | Écouteur de fin de reconnaissance |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScanner(ComponentActivity parentActivity) {#BarcodeScanner-androidx.activity.ComponentActivity-}
```
public BarcodeScanner(ComponentActivity parentActivity)
```


Initialise une nouvelle instance de la classe BarcodeScanner.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentActivity | androidx.activity.ComponentActivity | activité depuis laquelle BarcodeScanner est appelé. Doit être initialisée avant que la vue de l'activité parente ne soit créée |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences - préférences du scanner de code-barres
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


Lance la vue de la caméra et gère le processus de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeRecognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable | Instance personnalisée de la classe abstraite OnScannerRecognitionFinishedListener qui traite le résultat de la reconnaissance |

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


Écouteur de fin de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| onBarcodeScannerCompletedCallback | com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback | écouteur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

