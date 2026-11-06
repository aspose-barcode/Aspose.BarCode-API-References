---
title: "com.aspose.barcode.component.barcodescanner"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: 
type: docs
weight: 13
url: /el/androidjava/com.aspose.barcode.component.barcodescanner/
---

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [BarcodeRecognitionContract](../com.aspose.barcode.component.barcodescanner/barcoderecognitioncontract) | Εσωτερική BarcodeRecognitionContract απαιτείται για τη ρύθμιση της εξόδου BarcodeScannerActivity από την πελατειακή δραστηριότητα |
| [BarcodeRecognitionSettings](../com.aspose.barcode.component.barcodescanner/barcoderecognitionsettings) | Το BarcodeRecognitionSettings περιέχει το API για την προσαρμογή του BarcodeRecognitionFragment και τις ρυθμίσεις αναγνώρισης κωδίκων, η προσθήκη του RecognitionResultsHandler πρέπει να κληθεί πριν την έναρξη της διαδικασίας αναγνώρισης στο BarcodeScannerFragment. |
| [BarcodeScanner](../com.aspose.barcode.component.barcodescanner/barcodescanner) | Το BarcodeScanner περιέχει τη λειτουργικότητα που σχετίζεται με την αναγνώριση κωδίκων από την κάμερα της συσκευής Android. |
| [BarcodeScannerActivity](../com.aspose.barcode.component.barcodescanner/barcodescanneractivity) | Δραστηριότητα που περιέχει το BarcodeScannerFragment. Είναι εσωτερική κλάση και ο πελάτης δεν πρέπει να καλέσει αυτήν την κλάση, αλλά πρέπει να καταχωρήσει το BarcodeScannerActivity στο AndroidManifest.xml |
| [BarcodeScannerFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerfragment) | Fragment για την αναγνώριση κωδίκων. |
| [BarcodeScannerFragmentSettings](../com.aspose.barcode.component.barcodescanner/barcodescannerfragmentsettings) | Ρυθμίσεις για το BarcodeScannerFragmentSettings |
| [BarcodeScannerPreferences](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferences) | Οι προτιμήσεις του BarcodeScanner. |
| [BarcodeScannerPreferencesFragment](../com.aspose.barcode.component.barcodescanner/barcodescannerpreferencesfragment) | Το PreferencesFragment μπορεί να χρησιμοποιηθεί για την προσαρμογή της διαδικασίας αναγνώρισης κωδίκων χρησιμοποιώντας προσαρμοσμένο GUI. |
| [BarcodeScannerView](../com.aspose.barcode.component.barcodescanner/barcodescannerview) |  |
| [CameraProcessingFragment](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragment) | Εσωτερική |
| [CameraProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings) | Ρυθμίσεις για το CameraProcessingFragment |
| [RecognitionAreaSettings](../com.aspose.barcode.component.barcodescanner/recognitionareasettings) |  |
| [RecognitionAreaView](../com.aspose.barcode.component.barcodescanner/recognitionareaview) |  |
| [RecognitionProcessFragmentBitmapBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentbitmapbackground) | Αναπαριστά το φόντο της εικόνας που θα αποδοθεί κατά τη διάρκεια της διαδικασίας αναγνώρισης. |
| [RecognitionProcessFragmentCameraPhotoBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcameraphotobackground) | Αναπαριστά το φόντο της εικόνας που λαμβάνεται από την κάμερα και θα αποδοθεί κατά τη διάρκεια της διαδικασίας αναγνώρισης. |
| [RecognitionProcessFragmentColorBackground](../com.aspose.barcode.component.barcodescanner/recognitionprocessfragmentcolorbackground) | Αντιπροσωπεύει το μονοχρωματικό φόντο που θα αποδοθεί κατά τη διάρκεια της διαδικασίας αναγνώρισης |
| [RecognitionProcessingFragment](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragment) | Το εσωτερικό περιέχει το GUI που αποδόθηκε κατά τη διάρκεια της διαδικασίας αναγνώρισης |
| [RecognitionProcessingFragmentSettings](../com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings) |  |

## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [BarcodeRecognitionResultsHandler](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandler) | Διαχειριστής για την επεξεργασία των αποτελεσμάτων αναγνώρισης. Χρησιμοποιείται στην πλευρά της δραστηριότητας αναγνώρισης. |
| [BarcodeRecognitionResultsHandlerParcelable](../com.aspose.barcode.component.barcodescanner/barcoderecognitionresultshandlerparcelable) | Υλοποίηση του OnScannerRecognitionFinishedListener που υλοποιεί τη διεπαφή Parcelable. |
| [OnBarcodeScannerCompletedCallback](../com.aspose.barcode.component.barcodescanner/onbarcodescannercompletedcallback) | Ορισμός διεπαφής για μια κλήση επιστροφής που θα κληθεί όταν ολοκληρωθεί η διαδικασία σάρωσης. |
| [OnRecognitionPreferencesChangedListener](../com.aspose.barcode.component.barcodescanner/onrecognitionpreferenceschangedlistener) |  |

## Απαριθμήσεις

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [CameraMode](../com.aspose.barcode.component.barcodescanner/cameramode) | Περιέχει λειτουργίες για λήψη εικόνων από την κάμερα |
