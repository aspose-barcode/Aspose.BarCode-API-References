---
title: DecodeType
second_title: Aspose.BarCode για Αναφορά API .NET
description: Καθορίστε τον τύπο του γραμμικού κώδικα προς ανάγνωση.
type: docs
weight: 190
url: /el/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Καθορίστε τον τύπο του γραμμικού κώδικα προς ανάγνωση.

```csharp
public static class DecodeType
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Λαμβάνει έναν πίνακα που αντιπροσωπεύει AllSupportedTypes |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Ανακτά έναν πίνακα με τα ονόματα των τύπων αποκωδικοποίησης. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο[`BaseDecodeType`](../basedecodetype/) περιέχει οποιοδήποτε γραμμικό κώδικα 1D symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο[`BaseDecodeType`](../basedecodetype/) περιέχει οποιοδήποτε 2D barcode symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο[`BaseDecodeType`](../basedecodetype/) περιέχει οποιοδήποτε ταχυδρομικό γραμμικό κώδικα σύμβολο |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια επιστρεφόμενη τιμή υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Καθορισμός συνόλων σάρωσης ανά barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | Μετατρέπει την παράσταση συμβολοσειράς ενός MultyDecodeType στο στιγμιότυπο του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια επιστρεφόμενη τιμή υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Καθορίζει ότι τα δεδομένα θα ελέγχονται με όλες τις διαθέσιμες συμβολολογίες |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Γραμμωτός κώδικας eParcel της Αυστραλίας Ταχυδρομείου** προδιαγραφή γραμμικού κώδικα |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Australia Post** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Αζτέκοι** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **CODABAR** προδιαγραφή γραμμικού κώδικα |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **CodablockF** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ΚΩΔΙΚΟΣ 11** προδιαγραφή γραμμικού κώδικα |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ΚΩΔΙΚΟΣ 128** προδιαγραφή γραμμικού κώδικα |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός 16Κ** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός 32** κενή προδιαγραφή |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Εκτεταμένο ΚΩΔΙΚΟΣ 39** προδιαγραφή γραμμικού κώδικα |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Τυπικός ΚΩΔΙΚΟΣ 39** προδιαγραφή γραμμικού κώδικα |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Επέκταση ΚΩΔΙΚΟΣ 93** προδιαγραφή γραμμικού κώδικα |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Τυπικός ΚΩΔΙΚΟΣ 93** προδιαγραφή γραμμικού κώδικα |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **CompactPdf417** (Pdf417Truncated) Προδιαγραφή γραμμικού κώδικα |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Η γραμμή δεδομένων GS1 επεκτάθηκε** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Η γραμμή δεδομένων GS1 επεκτάθηκε σε στοίβα** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Η γραμμή δεδομένων GS1 είναι περιορισμένη** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Γραμμή δεδομένων GS1 πανκατευθυντική** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Γραμμή δεδομένων GS1 στοιβαγμένη** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Γραμμή δεδομένων GS1 στοιβαγμένη πανκατευθυντική** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Η γραμμή δεδομένων GS1 περικόπηκε** Προδιαγραφές γραμμικού κώδικα |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **DataLogic 2 από 5** κενή προδιαγραφή |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **DataMatrix** barcode symbology |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **DeutschePost Κωδικός αναγνώρισης** προδιαγραφή γραμμικού κώδικα |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός DeutschePost Leit** προδιαγραφή γραμμικού κώδικα |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **DotCode** κενή προδιαγραφή |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **DotCode** κενή προδιαγραφή |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **EAN-13** προδιαγραφή γραμμικού κώδικα |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **EAN14** Προδιαγραφές γραμμικού κώδικα |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ΕΑΝ-8** προδιαγραφή γραμμικού κώδικα |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **GS1 ΚΩΔΙΚΟΣ 128** προδιαγραφή γραμμικού κώδικα |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **GS1DataMatrix** barcode symbology |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **GS1 DotCode** κενή προδιαγραφή |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **GS1 QR** Προδιαγραφές γραμμικού κώδικα |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC LIC Αζτέκων** κενή προδιαγραφή |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC PAS Αζτέκων** κενή προδιαγραφή |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός HIBC LIC128** κενή προδιαγραφή |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός HIBC PAS128** κενή προδιαγραφή |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός HIBC LIC39** κενή προδιαγραφή |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός HIBC PAS39** κενή προδιαγραφή |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC LIC DataMatrix** κενή προδιαγραφή |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC PAS DataMatrix** κενή προδιαγραφή |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC LIC QR** κενή προδιαγραφή |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **HIBC PAS QR** κενή προδιαγραφή |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **IATA 2 από 5**προδιαγραφή γραμμικού κώδικα. Η IATA (International Air Transport Association) χρησιμοποιεί αυτόν τον γραμμωτό κώδικα για τη διαχείριση του αεροπορικού φορτίου. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ΠΑΡΕΜΕΒΕ 2 από 5** προδιαγραφή γραμμικού κώδικα |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ISBN** προδιαγραφή γραμμικού κώδικα |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ISMN** προδιαγραφή γραμμικού κώδικα |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ISSN** προδιαγραφή γραμμικού κώδικα |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Ιταλικά Ταχυδρομεία 25** προδιαγραφή γραμμικού κώδικα |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ITF14** Προδιαγραφές γραμμικού κώδικα |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **ITF6** προδιαγραφή γραμμικού κώδικα |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **MacroPdf417** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Royal Mail Mailmark** προδιαγραφή γραμμωτού κώδικα. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Matrix 2 από 5** προδιαγραφή γραμμικού κώδικα |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **MaxiCode** Προδιαγραφές γραμμικού κώδικα |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **MICR E-13B** κενή προδιαγραφή |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **MicroPdf417** Προδιαγραφές γραμμικού κώδικα |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός MicroQR** Προδιαγραφές γραμμικού κώδικα |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Καθορίζει ότι τα δεδομένα θα ελέγχονται με τα πιο συχνά χρησιμοποιούμενα symbologies |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **MSI Plessey** προδιαγραφή γραμμικού κώδικα |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Απροσδιόριστος τύπος αποκωδικοποίησης. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με USPS **OneCode** Προδιαγραφές γραμμικού κώδικα |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **OPC** προδιαγραφή γραμμικού κώδικα |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός ενημέρωσης κώδικα** προδιαγραφή γραμμικού κώδικα. Η συμβολολογία γραμμωτού κώδικα χρησιμοποιείται για αυτοματοποιημένη σάρωση |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Pdf417** barcode symbology |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Pharmacode** barcode. Αυτή η συμβολολογία είναι επίσης γνωστή ως Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Πλανήτης** Προδιαγραφές γραμμικού κώδικα |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Καθορίζει ότι τα δεδομένα θα ελέγχονται με όλα τα **Ταχυδρομείο 1,5D** συμβολολογίες γραμμωτού κώδικα, όπως **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Postnet** προδιαγραφή γραμμικού κώδικα |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **PZN** προδιαγραφή γραμμικού κώδικα. Αυτή η συμβολολογία είναι επίσης γνωστή ως Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Κωδικός QR** Προδιαγραφές γραμμικού κώδικα |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **RM4SCC** προδιαγραφή γραμμικού κώδικα. Το RM4SCC (Royal Mail 4-state Customer Code) χρησιμοποιείται για την αυτοματοποιημένη διαδικασία ταξινόμησης αλληλογραφίας στο ΗΒ. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **SCC14** Προδιαγραφές γραμμικού κώδικα |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **SSCC18** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Πρότυπο 2 από 5** προδιαγραφή γραμμικού κώδικα |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Συμπλήρωμα (EAN2, EAN5)** προδιαγραφή γραμμικού κώδικα |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **Swiss Post Parcel Barcode** Προδιαγραφές γραμμικού κώδικα |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Καθορίζει ότι τα δεδομένα θα ελέγχονται με όλα τα **1Δ** barcode symbologies |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Καθορίζει ότι τα δεδομένα θα ελέγχονται με όλα τα **2D** barcode symbologies |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **UPC-A** προδιαγραφή γραμμικού κώδικα |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **UPC-E** προδιαγραφή γραμμικού κώδικα |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιούνται με **VIN** (Αριθμός Αναγνώρισης Οχήματος) προδιαγραφή γραμμικού κώδικα |

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
