---
title: "BarcodeScanner"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Το BarcodeScanner περιέχει τη λειτουργικότητα που σχετίζεται με την αναγνώριση κωδίκων από την κάμερα της συσκευής Android."
type: docs
weight: 12
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/barcodescanner/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeScanner
```

Το BarcodeScanner περιέχει τη λειτουργικότητα που σχετίζεται με την αναγνώριση κωδίκων από την κάμερα της συσκευής Android.

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BarcodeScanner(ComponentActivity parentActivity)](#BarcodeScanner-androidx.activity.ComponentActivity-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeScanner. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPreferences()](#getPreferences--) |  |
| [hashCode()](#hashCode--) |  |
| [launchBarcodeScanner(BarcodeRecognitionResultsHandlerParcelable barcodeRecognitionResultsHandler)](#launchBarcodeScanner-com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable-) | Εκκινήστε την προβολή της κάμερας και διαχειριστείτε τη διαδικασία αναγνώρισης |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnBarcodeScannerCompletedCallback(OnBarcodeScannerCompletedCallback onBarcodeScannerCompletedCallback)](#setOnBarcodeScannerCompletedCallback-com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback-) | Ακροατής ολοκλήρωσης αναγνώρισης |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeScanner(ComponentActivity parentActivity) {#BarcodeScanner-androidx.activity.ComponentActivity-}
```
public BarcodeScanner(ComponentActivity parentActivity)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης BarcodeScanner.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentActivity | androidx.activity.ComponentActivity | Δραστηριότητα από την οποία κλήθηκε το BarcodeScanner. Πρέπει να αρχικοποιηθεί πριν δημιουργηθεί η προβολή της γονικής δραστηριότητας |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences - προτιμήσεις σαρωτή barcode
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


Εκκινήστε την προβολή της κάμερας και διαχειριστείτε τη διαδικασία αναγνώρισης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeRecognitionResultsHandler | com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable | Προσαρμοσμένο στιγμιότυπο της αφηρημένης κλάσης OnScannerRecognitionFinishedListener που επεξεργάζεται το αποτέλεσμα αναγνώρισης |

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


Ακροατής ολοκλήρωσης αναγνώρισης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| onBarcodeScannerCompletedCallback | com.aspose.barcode.component.barcodescanner.OnBarcodeScannerCompletedCallback | ακροατής |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

