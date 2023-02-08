---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode για Αναφορά API .NET
description: Barcode Windows Control μεταβείτε στον πίνακα εργαλείων σας και προσθέστε Aspose.BarCode.dll και θα δείτε να εμφανίζεται το BarcodeGeneratorControl. Απλώς σύρετέ το και αφήστε το στη φόρμα των Windows. βλ. βλ
type: docs
weight: 1320
url: /el/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

Barcode Windows Control, μεταβείτε στον πίνακα εργαλείων σας και προσθέστε Aspose.BarCode.dll, και θα δείτε να εμφανίζεται το BarcodeGeneratorControl. Απλώς σύρετέ το και αφήστε το στη φόρμα των Windows. βλ. βλ

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία με την οποία αλλάζει αυτόματα το μέγεθος του γραμμικού κώδικα. Η προεπιλεγμένη τιμή είναι AutoSizeMode. Καμία. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Χρώμα φόντου της εικόνας γραμμικού κώδικα. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | Ύψος εικόνας γραμμικού κώδικα όταν[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) Η ιδιότητα έχει οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Λαμβάνει ή ορίζει παραμέτρους padding barcode[`Padding`](../../aspose.barcode.generation/padding/) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Τύπος κωδικοποίησης του BarCode (συμβολολογία). Χρήση[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) για να πάρετε την τρέχουσα συμβολολογία. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | Πλάτος εικόνας BarCode όταν[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) Η ιδιότητα έχει οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Χρώμα ράβδων. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Ύψος γραμμών γραμμωτών κωδικών 1D. Αγνοήθηκε εάν[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) Η ιδιότητα έχει οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Λαμβάνει ή ορίζει παραμέτρους περιγράμματος[`BorderParameters`](../../aspose.barcode.generation/borderparameters/) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Λεζάντα Πάνω από την εικόνα BarCode. Βλέπω[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Λεζάντα Κάτω από την εικόνα BarCode. Βλέπω[`CaptionParameters`](../../aspose.barcode.generation/captionparameters/) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Να εμφανίζεται πάντα το ψηφίο του αθροίσματος ελέγχου στο αναγνώσιμο από τον άνθρωπο κείμενο για τους γραμμωτούς κώδικες Code128 και GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Δεδομένα προς κωδικοποίηση, διαφορετικοί τύποι BarCode ενδέχεται να έχουν διαφορετικούς περιορισμούς μήκους CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Λαμβάνει ή ορίζει παραμέτρους CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape/) { get; set; } | Υποδεικνύει εάν εξηγεί τον χαρακτήρα "\" ως χαρακτήρα διαφυγής στην ιδιότητα CodeText. Χρησιμοποιείται για Pdf417, DataMatrix, Code128 only Εάν το EnableEscape είναι αληθές, το "\" θα εξηγηθεί ως ειδικός χαρακτήρας διαφυγής. Διαφορετικά, το "\" λειτουργεί ως κανονικοί χαρακτήρες. Το Aspose.BarCode υποστηρίζει την εισαγωγή δεκαδικού κώδικα ascii και μνημονικού για χαρακτήρες κώδικα ελέγχου ASCII. Για παράδειγμα, \013 και \\CR σημαίνει CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Τύπος κωδικοποίησης του BarCode (συμβολολογία). Χρήση[`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) για να πάρετε την τρέχουσα συμβολολογία. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν γεμίζουν οι γραμμές. Μόνο για γραμμωτούς κώδικες 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Ενεργοποίηση αθροίσματος ελέγχου κατά τη δημιουργία γραμμωτών κωδίκων 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση της εικόνας BarCode. Μία τιμή και για τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. Γωνία Περιστροφής = 0 ή Γωνία Περιστροφής = 360 σημαίνει ότι δεν υπάρχει περιστροφή. Εάν η γωνία περιστροφής ΔΕΝ ισούται με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία του σαρωτή να διαβάσει__x00 την εικόνα. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Συγκεκριμένες παράμετροι |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Μόνο για γραμμωτούς κώδικες 1D. Εάν το κωδικοποιημένο κείμενο είναι λανθασμένο και η τιμή οριστεί σε true - θα γίνει εξαίρεση. Διαφορετικά, το κωδικοποιημένο κείμενο θα διορθωθεί ώστε να ταιριάζει με την προδιαγραφή του γραμμικού κώδικα. Θα γίνεται πάντα εξαίρεση για: Συμβολολογία γραμμής δεδομένων εάν το κωδικοποιημένο κείμενο είναι λανθασμένο. Η εξαίρεση δεν θα γίνεται πάντα για: AustraliaPost, SingapurePost, Code39Extended, Code9381Extended Coderectext, . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Λόγος ευρειών γραμμών προς στενές ράβδους. Προεπιλεγμένη τιμή: 3, δηλαδή, οι φαρδιές ράβδοι είναι 3 φορές μεγαλύτερες από τις στενές ράβδους. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, ItalianP2of5, MatrixP2ost2of5 , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | Η διάσταση Χ είναι το μικρότερο πλάτος της μονάδας γραμμών ή διαστημάτων BarCode. Αυξήστε αυτό θα αυξήσει ολόκληρο το πλάτος εικόνας γραμμικού κώδικα. Αγνοήθηκε εάν[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) Η ιδιότητα έχει οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |

### Δείτε επίσης

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* χώρος ονομάτων [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
