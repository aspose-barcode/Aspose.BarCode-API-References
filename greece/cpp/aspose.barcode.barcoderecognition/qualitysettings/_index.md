---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings class"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings class. Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxQuality ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality σε C++."
type: docs
weight: 3100
url: /el/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με εσφαλμένο κείμενο. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση. |
| [get_ComplexBackground](./get_complexbackground/)() const | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [get_Deconvolution](./get_deconvolution/)() const | Λειτουργία αποδιαστολής (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποδιαστολή είναι μια λειτουργία που μπορεί να αποκαταστήσει εικόνα που έχει υποβαθμιστεί (συνελικθεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με τη φωτογραφική μηχανή. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία που κακοποιεί την εικόνα, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η οξύτητα ή η μαθηματική μορφολογία. |
| static [get_HighPerformance](./get_highperformance/)() | Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία. |
| static [get_HighQuality](./get_highquality/)() | Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. Επιτρέπει τον εντοπισμό πολύ κατεστραμμένων barcode. |
| [get_InverseImage](./get_inverseimage/)() const | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcode σε εικόνες με ανεστραμμένα χρώματα (φωτεινότητα). |
| static [get_MaxQuality](./get_maxquality/)() | Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των πιθανών γραμμωτών κωδίκων, ακόμη και λανθασμένων γραμμωτών κωδίκων. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τους περισσότερους γραμμωτούς κώδικες. |
| [get_XDimension](./get_xdimension/)() const | Λειτουργία [Recognition](../../aspose.barcode.barcoderecognition.recognition/) που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή μπάρα. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με εσφαλμένο κείμενο. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode χαμηλότερης ποιότητας απαιτεί πιο απαιτητικές μεθόδους, κάτι που επιβραδύνει την αναγνώριση. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Λειτουργία αποδιαστολής (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποδιαστολή είναι μια λειτουργία που μπορεί να αποκαταστήσει εικόνα που έχει υποβαθμιστεί (συνελικθεί) από οποιαδήποτε φυσική λειτουργία όπως η θόλωση, κατά τη λήψη της εικόνας με τη φωτογραφική μηχανή. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία που κακοποιεί την εικόνα, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η οξύτητα ή η μαθηματική μορφολογία. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση barcode σε εικόνες με ανεστραμμένα χρώματα (φωτεινότητα). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Λειτουργία [Recognition](../../aspose.barcode.barcoderecognition.recognition/) που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή μπάρα. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [QualitySettings](./) με το [BarCodeReader](../barcodereader/)
```cpp
[C#]
//Ορίστε τη λειτουργία HighPerformance recogition
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Ορίστε τη λειτουργία HighQuality recognition
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Ορίστε τη λειτουργία HighPerformance recogition για barcode μικρού μεγέθους
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Ορίστε τη λειτουργία HighPerformance recogition για barcode χαμηλής ποιότητας
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
