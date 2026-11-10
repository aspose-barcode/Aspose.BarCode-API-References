---
title: "Enum DeconvolutionMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Λειτουργία αποκατάστασης εικόνας μέσω αποσυμπίεσης που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η αποσυμπίεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποστεί υποβάθμιση λόγω οποιασδήποτε φυσικής λειτουργίας όπως η θόλωση κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που την καταστρέφει, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η ευκρίνεια ή η μαθηματική μορφολογία"
type: docs
weight: 240
url: /el/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Αποσύνθεση (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η αποσύνθεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποβαθμιστεί (συνελικθεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία που κακοποιεί την εικόνα, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως το sharp ή τη μαθηματική μορφολογία.

```csharp
public enum DeconvolutionMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Fast | `0` | Ενεργοποιεί γρήγορες μεθόδους αποσυμπίεσης για εικόνες υψηλής ποιότητας |
| Normal | `1` | Ενεργοποιεί κανονικές μεθόδους αποδιαμόρφωσης για κοινές εικόνες. |
| Slow | `2` | Ενεργοποιεί αργές μεθόδους αποδιαμόρφωσης για εικόνες χαμηλής ποιότητας. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία Αποδιαμόρφωσης

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


