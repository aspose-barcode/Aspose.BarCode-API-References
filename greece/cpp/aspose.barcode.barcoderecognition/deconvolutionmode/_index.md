---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε enum σε C++."
type: docs
weight: 3800
url: /el/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Γρήγορο | 0 | Ενεργοποιεί γρήγορες μεθόδους αποσύνθεσης για εικόνες υψηλής ποιότητας. |
| Κανονική | 1 | Ενεργοποιεί κανονικές μεθόδους αποσύνθεσης για κοινές εικόνες. |
| Αργό | 2 | Ενεργοποιεί αργές μεθόδους αποσύνθεσης για εικόνες χαμηλής ποιότητας. |

## Σχόλια


Λειτουργία αποδιαστολής (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποδιαστολή είναι μια λειτουργία που μπορεί να αποκαταστήσει εικόνα που έχει υποβαθμιστεί (συνελικθεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με τη φωτογραφική μηχανή. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία που κακοποιεί την εικόνα, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η οξύτητα ή η μαθηματική μορφολογία.

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
