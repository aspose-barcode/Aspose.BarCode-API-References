---
title: "Κλάση QualitySettings"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.QualitySettings. Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές HighPerformance, NormalQuality, HighQuality, MaxQuality ή να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality."
type: docs
weight: 370
url: /el/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxQuality ή να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

```csharp
public sealed class QualitySettings
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. Επιτρέπει τον εντοπισμό πολύ κατεστραμμένων barcode. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των δυνατών barcode, ακόμη και λανθασμένων barcode. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksumm ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με εσφαλμένο κείμενο. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Ένα στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcodes σε χρωματικές εικόνες. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Αποσύνθεση (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά, η αποσύνθεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποβαθμιστεί (συνελικθεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία που κακοποιεί την εικόνα, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως το sharp ή τη μαθηματική μορφολογία. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcodes σε εικόνες με ανεστραμμένα χρώματα (φωτεινότητα). |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου barcode: κελί πλέγματος ή μπάρα. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το QualitySettings με το BarCodeReader

```csharp
[C#]
//ορίστε τη λειτουργία αναγνώρισης HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//ορίστε τη λειτουργία αναγνώρισης HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//ορίστε τη λειτουργία αναγνώρισης HighPerformance για barcode μικρού μεγέθους
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//ορίστε τη λειτουργία αναγνώρισης HighPerformance για barcode χαμηλής ποιότητας
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


