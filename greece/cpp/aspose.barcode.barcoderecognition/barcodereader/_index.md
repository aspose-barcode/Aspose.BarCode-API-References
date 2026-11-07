---
title: "κλάση Aspose::BarCode::BarCodeRecognition::BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "κλάση Aspose::BarCode::BarCodeRecognition::BarCodeReader. Το BarCodeReader περιλαμβάνει μια εικόνα που μπορεί να περιέχει έναν ή πολλούς barcode, και μπορεί στη συνέχεια να εκτελέσει τη λειτουργία ReadBarCodes για την ανίχνευση barcode σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Abort](./abort/)() | Η συνάρτηση ζητά τη λήξη της τρέχουσας συνεδρίας αναγνώρισης από άλλο νήμα. Η Abort είναι μέθοδος που δεν μπορεί να αποκλειστεί και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης διαρκεί πολύ. |
| [BarCodeReader](./barcodereader/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./) με προεπιλεγμένες τιμές. Απαιτεί να ορίσετε εικόνα (SetBitmapImage()) πριν καλέσετε τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./) από μια εικόνα. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./) από αρχείο. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](./) από ένα πλαίσιο φωτεινότητας. |
| [Dispose](./dispose/)() override | Απελευθέρωση πόρου |
| [ExportToXml](./exporttoxml/)(System::String) | Εξάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) σε καθορισμένο αρχείο xml |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Εξάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) σε καθορισμένη ροή xml |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Λαμβάνει τον τύπο αποκωδικοποίησης barcode που χρησιμοποιείται για την αναγνώριση. Πρέπει να οριστεί πριν την κλήση του [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | Οι κύριες παράμετροι αποκωδικοποίησης του [BarCode](../../aspose.barcode/). Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Λαμβάνει τον πίνακα των αναγνωρισμένων [BarCodeResult](../barcoderesult/) |
| [get_FoundCount](./get_foundcount/)() | Λαμβάνει τον αριθμό των αναγνωρισμένων barcode |
| static [get_ProcessorSettings](./get_processorsettings/)() | Λαμβάνει τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το [QualitySettings](../qualitysettings/) με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του [QualitySettings](../qualitysettings/) είναι NormalQuality. |
| [get_Timeout](./get_timeout/)() | Λαμβάνει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| static [ImportFromXml](./importfromxml/)(System::String) | Εισάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) από το καθορισμένο αρχείο xml και τις εφαρμόζει στην τρέχουσα παρουσία του [BarCodeReader](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Εισάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) από το καθορισμένο ροή xml και τις εφαρμόζει στην τρέχουσα παρουσία του [BarCodeReader](./). |
| [ReadBarCodes](./readbarcodes/)() | Αναγνάζει τα [BarCodeResult](../barcoderesult/) από την εικόνα. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Ορίζει τον τύπο αποκωδικοποίησης barcode που χρησιμοποιείται για την αναγνώριση. Πρέπει να οριστεί πριν από την κλήση του [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το [QualitySettings](../qualitysettings/) με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του [QualitySettings](../qualitysettings/) είναι NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Ορίζει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Ορίζει την εικόνα bitmap για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Ορίζει την εικόνα bitmap και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Ορίζει την εικόνα bitmap και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Ορίζει το αρχείο εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Ορίζει τη ροή εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Ορίζει το πλαίσιο φωτεινότητας και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Ορίζει το πλαίσιο φωτεινότητας και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Ορίζει το πλαίσιο φωτεινότητας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Ορίζει τον πίνακα τύπων [SingleDecodeType](../singledecodetype/) για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [ReadBarCodes()](./readbarcodes/). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε τα barcodes Code39 και Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
