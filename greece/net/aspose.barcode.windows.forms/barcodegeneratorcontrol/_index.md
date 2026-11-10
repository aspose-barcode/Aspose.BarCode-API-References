---
title: "Κλάση BarCodeGeneratorControl"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl κλάση. BarCode Windows Control μεταβείτε στο πάνελ εργαλείων σας και προσθέστε το Aspose.BarCode.dll και θα δείτε το BarcodeGeneratorControl να εμφανίζεται. Απλώς σύρετε το και τοποθετήστε το στη Windows φόρμα σας. δείτε  δείτε"
type: docs
weight: 1800
url: /el/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, μεταβείτε στον πίνακα εργαλείων σας και προσθέστε το Aspose.BarCode.dll, και θα δείτε το BarcodeGeneratorControl να εμφανίζεται. Απλώς σύρετε το και τοποθετήστε το στη φόρμα Windows σας. δείτε  δείτε

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία με την οποία το barcode αλλάζει αυτόματα το μέγεθος. Προεπιλεγμένη τιμή είναι AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Χρώμα φόντου της εικόνας barcode. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | Ύψος εικόνας BarCode όταν η ιδιότητα [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Λαμβάνει ή ορίζει τις παραμέτρους περιθωρίων Barcode [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Τύπος κωδικοποίησης του BarCode (συμβολισμός). Χρησιμοποιήστε το [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) για να λάβετε τον τρέχοντα συμβολισμό. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | Πλάτος εικόνας BarCode όταν η ιδιότητα [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Χρώμα γραμμών. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Ύψος των γραμμών των 1D barcodes. Αγνοείται εάν η ιδιότητα [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Λαμβάνει ή ορίζει τις παραμέτρους περιγράμματος [`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Λεζάντα πάνω από την εικόνα BarCode. Δείτε το [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Λεζάντα κάτω από την εικόνα BarCode. Δείτε το [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Πάντα να εμφανίζεται το ψηφίο ελέγχου στο κείμενο αναγνώσιμο από άνθρωπο για τους γραμμωτούς κώδικες Code128 και GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Δεδομένα προς κωδικοποίηση, διαφορετικοί τύποι BarCode μπορεί να έχουν διαφορετικούς περιορισμούς μήκους CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Λαμβάνει ή ορίζει τις παραμέτρους CodeText [`CodetextParametersUI`](../codetextparametersui/). |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Τύπος κωδικοποίησης του BarCode (συμβολισμός). Χρησιμοποιήστε το [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) για να λάβετε τον τρέχοντα συμβολισμό. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Μόνο για 1D barcodes. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία 1D barcodes. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση της εικόνας BarCode. Μία τιμή και για τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για τον σαρωτή να διαβάσει την εικόνα. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Συγκεκριμένες παράμετροι |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Μόνο για 1D barcode. Εάν το codetext είναι λανθασμένο και η τιμή οριστεί σε true - θα προκληθεί εξαίρεση. Διαφορετικά το codetext θα διορθωθεί ώστε να ταιριάζει με τις προδιαγραφές του barcode. Η εξαίρεση πάντα θα προκληθεί για: συμβολική Databar εάν το codetext είναι λανθασμένο. Η εξαίρεση ποτέ δεν θα προκληθεί για: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 εάν το codetext είναι λανθασμένο. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο φαρδιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | Η διάσταση X είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτού θα αυξήσει το συνολικό πλάτος της εικόνας barcode. Αγνοείται εάν η ιδιότητα [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |

### Δείτε επίσης

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


