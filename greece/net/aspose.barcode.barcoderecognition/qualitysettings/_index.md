---
title: QualitySettings
second_title: Aspose.BarCode για Αναφορά API .NET
description: Το QualitySettings επιτρέπει τη μη αυτόματη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε να ρυθμίσετε γρήγορα τις Ρυθμίσεις Ποιότητας με ενσωματωμένες προεπιλογές High Performance NormalQuality HighQuality MaxBarCodes ή μπορείτε να ρυθμίσετε χειροκίνητα τις παραμέτρους του QualitySettings000_x.
type: docs
weight: 270
url: /el/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

Το QualitySettings επιτρέπει τη μη αυτόματη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε να ρυθμίσετε γρήγορα τις Ρυθμίσεις Ποιότητας με ενσωματωμένες προεπιλογές: High Performance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να ρυθμίσετε χειροκίνητα τις παραμέτρους του QualitySettings000_x.

```csharp
public sealed class QualitySettings
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης υψηλής απόδοσης. Οι γραμμωτοί κώδικες υψηλής ποιότητας αναγνωρίζονται καλά σε αυτήν τη λειτουργία. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης υψηλής ποιότητας. Αυτή η προεπιλογή έχει αναπτυχθεί για γραμμικούς κώδικες χαμηλής ποιότητας. Επιτρέπει την ανίχνευση διαγώνιων και πολύ κατεστραμμένων γραμμωτών κωδίκων. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης HighQualityDetection. Ίδιο με το NormalQuality αλλά με υψηλή ποιότητα[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης MaxBarCodes. Αυτή η προεπιλογή έχει αναπτυχθεί για να αναγνωρίζει όλους τους πιθανούς γραμμωτούς κώδικες, ακόμη και τους λανθασμένους γραμμικούς κώδικες. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης MaxQualityDetection. Ίδιο με το NormalQuality αλλά με την υψηλότερη ποιότητα[`DetectorSettings`](./detectorsettings/) . Επιτρέπει τον εντοπισμό διαγώνιων και κατεστραμμένων γραμμωτών κωδίκων. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | Προκαθορισμένη ποιότητα αναγνώρισης NormalQuality. Κατάλληλο για τα περισσότερα barcodes |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει έγχρωμους γραμμωτούς κώδικες σε έγχρωμο φόντο ως πρόσθετη σάρωση. Εξαιρετικά αργή λειτουργία. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | Επιτρέπει στον κινητήρα για το Datamatrix να αναγνωρίζει διακεκομμένους βιομηχανικούς γραμμωτούς κώδικες Datamatrix. Αργή λειτουργία που βοηθά μόνο για διακεκομμένους γραμμωτούς κώδικες που αποτελούνται από σημεία. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίσει τη μειωμένη εικόνα ως πρόσθετη σάρωση. Το μέγεθος για μείωση επιλέγεται από εσωτερικούς αλγόριθμους κινητήρα. Η λειτουργία βοηθά στην αναγνώριση των γραμμωτών κωδίκων που είναι θόρυβοι και θολοί αλλά καταγράφονται με υψηλή ανάλυση. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | Επιτρέπει στον κινητήρα να χρησιμοποιεί το κενό μεταξύ των σαρώσεων για να αυξήσει την ταχύτητα αναγνώρισης. Η λειτουργία μπορεί να δημιουργήσει προβλήματα αναγνώρισης με γραμμωτούς κώδικες χαμηλού ύψους. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει γραμμικούς κώδικες που έχουν λανθασμένο άθροισμα ελέγχου ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για να αναγνωρίσει κατεστραμμένους γραμμωτούς κώδικες με εσφαλμένο κείμενο. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει αντίστροφη έγχρωμη εικόνα ως πρόσθετη σάρωση. Η λειτουργία μπορεί να χρησιμοποιηθεί όταν ο γραμμωτός κώδικας είναι λευκός σε μαύρο φόντο. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | Επιτρέπει στον κινητήρα να ενεργοποιήσει τη μέση εξομάλυνση ως πρόσθετη σάρωση. Η λειτουργία βοηθά στην αναγνώριση γραμμωτών κωδίκων με θόρυβο. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | Επιτρέπει στον κινητήρα για ταχυδρομικούς γραμμωτούς κώδικες να αναγνωρίζει εικόνες με ελαφρύ θόρυβο. Η λειτουργία βοηθά στην αναγνώριση ταχυδρομικών γραμμωτών κωδίκων που έχουν υποστεί ελαφρά ζημιά. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | Επιτρέπει στον κινητήρα για γραμμωτούς κώδικες 1D να αναγνωρίζει γρήγορα γραμμικούς κώδικες υψηλής ποιότητας που γεμίζουν σχεδόν ολόκληρη την εικόνα. Η λειτουργία βοηθά στη γρήγορη αναγνώριση των γραμμωτών κωδίκων που δημιουργούνται από το Διαδίκτυο. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | Επιτρέπει στον κινητήρα για γραμμωτούς κώδικες 1D να αναγνωρίζει γραμμικούς κώδικες με μεμονωμένες σκουπισμένες/κολλημένες ράβδους σε μοτίβο. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | Επιτρέπει στον κινητήρα για QR/MicroQR να αναγνωρίζει κατεστραμμένους γραμμωτούς κώδικες MicroQR. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει κανονική εικόνα χωρίς αποκαταστάσεις ως κύρια σάρωση. Λειτουργία αναγνώρισης εικόνας ως έχει. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει γραμμικούς κώδικες με τύπο θορύβου αλατιού και χαρτιού. Η λειτουργία μπορεί να αφαιρέσει μικρό θόρυβο με λευκές και μαύρες κουκκίδες. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει την εικόνα χωρίς μικρές λευκές κηλίδες ως πρόσθετη σάρωση. Η λειτουργία βοηθά στην αναγνώριση της εικόνας με θόρυβο καθώς και στο φιλτράρισμα της μέσης εξομάλυνσης. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει γραμμωτούς κώδικες 1D με άθροισμα ελέγχου ελέγχοντας περισσότερες παραλλαγές αναγνώρισης. Προεπιλεγμένη τιμή: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | Ρυθμίσεις ανιχνευτή γραμμικού κώδικα. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | Επιτρέπει στον κινητήρα για γραμμωτούς κώδικες 1D να αναγνωρίζει γρήγορα το μεσαίο κομμάτι μιας εικόνας και να επιστρέφει το αποτέλεσμα χωρίς τη χρήση χρονοβόρων αλγορίθμων. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | Μέγεθος παραθύρου για μέση εξομάλυνση. Οι τυπικές τιμές είναι 3 ή 4. Η προεπιλεγμένη τιμή είναι 3. Πρέπει να οριστεί το AllowMedianSmoothing. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | Επιτρέπει στον κινητήρα να αναγνωρίζει μικροσκοπικούς γραμμωτούς κώδικες σε μεγάλες εικόνες. Αγνοήθηκε αν[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/) έχει οριστεί σε True. Προεπιλεγμένη τιμή: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | Μεταβαίνει στον παλιό ανιχνευτή γραμμικού κώδικα. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να χρησιμοποιήσετε τις ρυθμίσεις ποιότητας με το BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ρυθμίστε τη λειτουργία υψηλής απόδοσης
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //Η λειτουργία κανονικής ποιότητας έχει οριστεί από προεπιλογή
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ρυθμίστε τη λειτουργία υψηλής ποιότητας με αναγνώριση χαμηλής ταχύτητας 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ρυθμίστε τη λειτουργία μέγιστου γραμμικού κώδικα, η οποία προσπαθεί να βρει όλους τους πιθανούς γραμμωτούς κώδικες, ακόμη και λανθασμένους. Η πιο αργή λειτουργία αναγνώρισης
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ρυθμίστε τη λειτουργία υψηλής απόδοσης
   reader.QualitySettings = QualitySettings.HighPerformance;
   //ορίστε ξεχωριστές επιλογές
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //Η προεπιλεγμένη λειτουργία είναι NormalQuality
   //ορίστε ξεχωριστές επιλογές
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ρυθμίστε τη λειτουργία υψηλής απόδοσης
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'Η λειτουργία κανονικής ποιότητας έχει οριστεί από προεπιλογή
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ρυθμίστε τη λειτουργία υψηλής ποιότητας με αναγνώριση χαμηλής ταχύτητας
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ορίστε τη λειτουργία μέγιστου γραμμικού κώδικα, η οποία προσπαθεί να βρει όλους τους πιθανούς γραμμωτούς κώδικες, ακόμη και λανθασμένους. Η πιο αργή λειτουργία αναγνώρισης
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'ρυθμίστε τη λειτουργία υψηλής απόδοσης
   reader.QualitySettings = QualitySettings.HighPerformance
   'ορίστε ξεχωριστές επιλογές
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'Η προεπιλεγμένη λειτουργία είναι NormalQuality
   'ορίστε ξεχωριστές επιλογές
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
