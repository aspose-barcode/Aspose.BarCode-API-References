---
title: "Κλάση BarCodeReader"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.BarCodeReader. Το BarCodeReader περιλαμβάνει μια εικόνα που μπορεί να περιέχει ένα ή πολλά barcode· στη συνέχεια μπορεί να εκτελέσει τη λειτουργία ReadBarCodes για την ανίχνευση των barcode"
type: docs
weight: 70
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

Το BarCodeReader περιλαμβάνει μια εικόνα που μπορεί να περιέχει ένα ή πολλά barcode, και στη συνέχεια μπορεί να εκτελέσει τη λειτουργία ReadBarCodes για την ανίχνευση barcode.

```csharp
public class BarCodeReader : Component
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader` με προεπιλεγμένες τιμές. Απαιτεί τον ορισμό της εικόνας (SetBitmapImage()) πριν καλέσετε τη μέθοδο ReadBarCodes(). |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader` από μια εικόνα. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader` από ένα πλαίσιο φωτεινότητας. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader` από αρχείο. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `BarCodeReader`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Ανακτά ή ορίζει τον τύπο αποκωδικοποίησης barcode που χρησιμοποιείται για την αναγνώριση. Πρέπει να οριστεί πριν την κλήση του [`ReadBarCodes`](./readbarcodes/). |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Οι κύριες παραμέτρους αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Ανακτά τον πίνακα των αναγνωρισμένων [`BarCodeResult`](../barcoderesult/) |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Ανακτά τον αριθμό των αναγνωρισμένων barcode |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings χρησιμοποιώντας ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Ανακτά ή ορίζει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Ανακτά τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και τις εφαρμόζει στο τρέχον αντικείμενο BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-file και τις εφαρμόζει στο τρέχον αντικείμενο BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Η λειτουργία ζητά τη λήξη της τρέχουσας συνεδρίας αναγνώρισης από άλλο νήμα. Η Abort είναι μέθοδος που δεν μπορεί να διακοπεί και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης είναι πολύ μακριά. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-stream |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-file |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Διαβάζει τα [`BarCodeResult`](../barcoderesult/) από την εικόνα. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Ορίζει την bitmap εικόνα για την αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Ορίζει το πλαίσιο φωτεινότητας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Ορίζει τη ροή εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Ορίζει το αρχείο εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Ορίζει την bitmap εικόνα και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Ορίζει την bitmap εικόνα και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Ορίζει το πλαίσιο φωτεινότητας και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Ορίζει το πλαίσιο φωτεινότητας και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Ορίζει τον πίνακα τύπου [`SingleDecodeType`](../singledecodetype/) για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
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

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


