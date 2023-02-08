---
title: BarCodeReader
second_title: Aspose.BarCode για Αναφορά API .NET
description: Το BarCodeReader ενσωματώνει μια εικόνα που μπορεί να περιέχει έναν ή περισσότερους γραμμικούς κώδικες και στη συνέχεια μπορεί να εκτελέσει τη λειτουργία ReadBarCodes για να ανιχνεύσει γραμμικούς κώδικες.
type: docs
weight: 60
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

Το BarCodeReader ενσωματώνει μια εικόνα που μπορεί να περιέχει έναν ή περισσότερους γραμμικούς κώδικες και στη συνέχεια μπορεί να εκτελέσει τη λειτουργία ReadBarCodes για να ανιχνεύσει γραμμικούς κώδικες.

```csharp
public class BarCodeReader : Component
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` κλάση με προεπιλεγμένες τιμές. Απαιτεί να ορίσετε την εικόνα (SetBitmapImage()) πριν να καλέσετε τη μέθοδο ReadBarCodes(). |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη από εικόνα. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη από αρχείο. |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία του`BarCodeReader` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Οι κύριες παράμετροι αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Αναγνωρίζεται[`BarCodeResult`](../barcoderesult/)s πίνακας |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Λαμβάνει αναγνωρισμένο αριθμό γραμμωτών κωδικών |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | Το QualitySettings επιτρέπει τη μη αυτόματη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε να ρυθμίσετε γρήγορα τις Ρυθμίσεις Ποιότητας με ενσωματωμένες προεπιλογές: High Performance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να ρυθμίσετε χειροκίνητα τις παραμέτρους του QualitySettings000_x. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Λαμβάνει ή ορίζει το χρονικό όριο λήξης της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Λαμβάνει ρυθμίσεις χρήσης πυρήνων επεξεργαστή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Εισάγει ιδιότητες BarCode από την καθορισμένη ροή xml και τις εφαρμόζει στην τρέχουσα παρουσία BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Εισάγει ιδιότητες BarCode από το καθορισμένο αρχείο xml και τις εφαρμόζει στην τρέχουσα παρουσία του BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Η συνάρτηση ζητά τερματισμό της τρέχουσας περιόδου σύνδεσης αναγνώρισης από άλλο νήμα. Το Abort είναι μέθοδος με δυνατότητα απεμπλοκής και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. Η μέθοδος θα πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης είναι πολύ μεγάλη. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Εξάγει ιδιότητες BarCode στη ροή xml specified |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Εξάγει ιδιότητες BarCode στο αρχείο xml specified |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Διαβάζει[`BarCodeResult`](../barcoderesult/) s από την εικόνα. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | Ορίζει την εικόνα bitmap για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | Ρυθμίζει τη ροή εικόνας για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | Ορίζει το αρχείο εικόνας για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | Ορίζει την εικόνα bitmap και την περιοχή για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | Ορίζει την εικόνα bitmap και τις περιοχές για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | Ορίζει τον τύπο αποκωδικοποίησης για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | Σετ[`SingleDecodeType`](../singledecodetype/) τύπου πίνακα για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
