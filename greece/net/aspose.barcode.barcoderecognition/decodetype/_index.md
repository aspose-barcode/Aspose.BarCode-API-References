---
title: "Κλάση DecodeType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.DecodeType. Καθορίστε τον τύπο του barcode για ανάγνωση"
type: docs
weight: 230
url: /el/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Καθορίστε τον τύπο του barcode για ανάγνωση.

```csharp
public static class DecodeType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Λαμβάνει έναν πίνακα που αντιπροσωπεύει το AllSupportedTypes |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Ανακτά έναν πίνακα με τα ονόματα των τύπων αποκωδικοποίησης. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο [`BaseDecodeType`](../basedecodetype/) περιέχει οποιαδήποτε 1D barcode συμβολική |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο [`BaseDecodeType`](../basedecodetype/) περιέχει οποιαδήποτε 2D barcode συμβολική |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Καθορίζει εάν το καθορισμένο [`BaseDecodeType`](../basedecodetype/) περιέχει οποιαδήποτε ταχυδρομική barcode συμβολική |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Καθορίστε σύνολα σάρωσης ανά barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις διαθέσιμες συμβολές |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australian Post Domestic eParcel Barcode** |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australia Post** |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Aztec** |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODABAR** |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CodablockF** |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODE 11** |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODE 128** |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **SCode16K** |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Code32** |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Code 39** βασικού συνόλου χαρακτήρων: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Code 39** πλήρους συνόλου χαρακτήρων ASCII: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CODE 93** |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CompactPdf417** (Pdf417Truncated) |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar expanded** |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar expanded stacked** |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar limited** |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar omni-directional** |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar stacked** |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar stacked omni-directional** |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar truncated** |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **DataLogic 2 of 5** |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με συμβολική αναπαράσταση barcode **DataMatrix** |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **DeutschePost Ident code** |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **DeutschePost Leit code** |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **DotCode** |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **DotCode** |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **EAN-13** |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **EAN14** |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **EAN-8** |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Aztec** |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 CODE 128** |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Composite Bar** |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με συμβολική αναπαράσταση barcode **GS1DataMatrix** |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 DotCode** |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Han Xin Code** |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroPdf417** |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 QR** |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Han Xin Code** |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC Aztec** |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS Aztec** |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC Code128** |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS Code128** |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC Code39** |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS Code39** |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC DataMatrix** |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS DataMatrix** |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC QR** |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS QR** |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **IATA 2 of 5**. IATA (International Air Transport Association) χρησιμοποιεί αυτό το barcode για τη διαχείριση του αεροπορικού φορτίου. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **INTERLEAVED 2 of 5** |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISBN** |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISMN** |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISSN** |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Italian Post 25** |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ITF14** |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ITF6** |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Japan Post** |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MacroPdf417** |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Royal Mail Mailmark**. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Matrix 2 of 5** |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MaxiCode** |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MICR E-13B** |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroPdf417** |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroQR Code** |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με τους πιο συχνά χρησιμοποιούμενους συμβολισμούς |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MSI Plessey** |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Μη καθορισμένος τύπος αποκωδικοποίησης. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode USPS **OneCode** |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **OPC** |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Patch code**. Ο συμβολισμός barcode χρησιμοποιείται για αυτοματοποιημένη σάρωση |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με συμβολισμό barcode **Pdf417** |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με barcode **Pharmacode**. Αυτός ο συμβολισμός είναι επίσης γνωστός ως Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Planet** |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους barcode συμβολισμούς **1.5D Postal**, όπως **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Postnet** |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **PZN**. Αυτός ο συμβολισμός είναι επίσης γνωστός ως Pharma Zentral Nummer. Υποστηρίζονται τα PZN7 και PZN8. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **QR Code** |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RectMicroQR (rMQR) Code** |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RM4SCC**. Το RM4SCC (Royal Mail 4-state Customer Code) χρησιμοποιείται για αυτοματοποιημένη διαδικασία ταξινόμησης αλληλογραφίας στο Ηνωμένο Βασίλειο. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SCC14** |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SSCC18** |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Standard 2 of 5** |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Supplement(EAN2, EAN5)** |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Swiss Post Parcel Barcode** |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους barcode συμβολισμούς **1D** |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους barcode συμβολισμούς **2D** |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-A** |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-E** |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **VIN** (Αριθμός Ταυτότητας Οχήματος) |

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


