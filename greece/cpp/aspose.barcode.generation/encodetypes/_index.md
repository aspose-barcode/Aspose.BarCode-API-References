---
title: "Aspose::BarCode::Generation::EncodeTypes κλάση"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::EncodeTypes κλάση. Καθορίζει τον τύπο του barcode που θα κωδικοποιηθεί σε C++."
type: docs
weight: 2300
url: /el/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Καθορίζει τον τύπο του barcode για κωδικοποίηση.

```cpp
class EncodeTypes
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις διαθέσιμες συμβολισμούς. |
| static [GetNames](./getnames/)() | Ανακτά έναν πίνακα με τα ονόματα των τύπων κωδικοποίησης. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Μετατρέπει τη συμβολοσειρά ενός [BaseEncodeType](../baseencodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Μετατρέπει τη συμβολοσειρά ενός [BaseEncodeType](../baseencodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Australian Post Domestic eParcel Barcode**. |
| static [AustraliaPost](./australiapost/) | Αναπαριστά το [BarCode](../../aspose.barcode/) του πελάτη Australia Post. |
| static [Aztec](./aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Aztec**. |
| static [Codabar](./codabar/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **CODABAR** |
| static [CodablockF](./codablockf/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Codablock-F**. |
| static [Code11](./code11/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **CODE 11** |
| static [Code128](./code128/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **CODE 128** |
| static [Code16K](./code16k/) | Αναπαριστά το barcode Code 16K. |
| static [Code32](./code32/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Code32** |
| static [Code39](./code39/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Code 39** βασικού συνόλου χαρακτήρων: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Code 39** πλήρους συνόλου χαρακτήρων ASCII: ISO/IEC 16388 |
| static [Code93](./code93/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **CODE 93** |
| static [DatabarExpanded](./databarexpanded/) | Αναπαριστά το επεκταμένο barcode GS1 Databar. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Αναπαριστά το επεκταμένο στοίβακτο barcode GS1 Databar. |
| static [DatabarLimited](./databarlimited/) | Αναπαριστά το περιορισμένο barcode GS1 Databar. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar omni-directional**. |
| static [DatabarStacked](./databarstacked/) | Αναπαριστά το στοίβακτο barcode GS1 Databar. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Αναπαριστά το barcode GS1 Databar stacked omni-directional. |
| static [DatabarTruncated](./databartruncated/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar truncated**. |
| static [DataLogic2of5](./datalogic2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **DataLogic 2 of 5** |
| static [DataMatrix](./datamatrix/) | Σύμβολο barcode 2Δ DataMatrix. |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Αναπαριστά το barcode Deutsch Post, αυτή η συμβολή είναι επίσης γνωστή ως Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Αναπαριστά το barcode Deutsch Post Leitcode, επίσης γνωστό ως German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **DotCode** |
| static [DutchKIX](./dutchkix/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Dutch KIX** |
| static [EAN13](./ean13/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **EAN-13** |
| static [EAN14](./ean14/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **EAN14** |
| static [EAN8](./ean8/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **EAN-8** |
| static [GS1Aztec](./gs1aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1 Aztec**. Το κείμενο κώδικα πρέπει να περιέχει παρενθέσεις για AI. |
| static [GS1CodablockF](./gs1codablockf/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1 Codablock-F**. Το κείμενο κώδικα πρέπει να περιέχει παρενθέσεις για AI. |
| static [GS1Code128](./gs1code128/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1 Code 128**. Το κείμενο κώδικα πρέπει να περιέχει παρενθέσεις για AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1 Composite Bar**. Το κείμενο κώδικα πρέπει να περιέχει παρενθέσεις για AI. Το κείμενο κώδικα 1D και το κείμενο κώδικα 2D πρέπει να διαχωρίζονται με το σύμβολο '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | Σύμβολο barcode 2D DataMatrix με μορφή συμβολοσειράς GS1 |
| static [GS1DotCode](./gs1dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1 DotCode**. Το κείμενο κώδικα πρέπει να περιέχει παρενθέσεις για AI. |
| static [GS1HanXin](./gs1hanxin/) | Σύμβολο barcode 2D HanXin με μορφή συμβολοσειράς GS1 |
| static [GS1MicroPdf417](./gs1micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **GS1MicroPdf417** |
| static [GS1QR](./gs1qr/) | Σύμβολο barcode 2D QR με μορφή συμβολοσειράς GS1 |
| static [HanXin](./hanxin/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **Han Xin** |
| static [HIBCAztecLIC](./hibcazteclic/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC LIC Aztec**. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC PAS Aztec**. |
| static [HIBCCode128LIC](./hibccode128lic/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC LIC Code128**. |
| static [HIBCCode128PAS](./hibccode128pas/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC PAS Code128**. |
| static [HIBCCode39LIC](./hibccode39lic/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC LIC Code39**. |
| static [HIBCCode39PAS](./hibccode39pas/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC PAS Code39**. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC LIC DataMatrix**. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC PAS DataMatrix**. |
| static [HIBCQRLIC](./hibcqrlic/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC LIC QR**. |
| static [HIBCQRPAS](./hibcqrpas/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **HIBC PAS QR**. |
| static [IATA2of5](./iata2of5/) | Αναπαριστά το barcode IATA 2 of 5. Η IATA (Διεθνής Ένωση Μεταφορών Αεροπορικού Φορτίου) χρησιμοποιεί αυτό το barcode για τη διαχείριση του αεροπορικού φορτίου. |
| static [Interleaved2of5](./interleaved2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **ISBN** |
| static [ISMN](./ismn/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **ISMN** |
| static [ISSN](./issn/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν σύμφωνα με προδιαγραφή barcode **ISSN** |
| static [ItalianPost25](./italianpost25/) | Αντιπροσωπεύει τον κώδικα 25 της Italian Post. |
| static [ITF14](./itf14/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **ITF14** |
| static [ITF6](./itf6/) | Αντιπροσωπεύει τον κώδικα ITF-6 barcode. |
| static [JapanPost](./japanpost/) | Αντιπροσωπεύει την Japan Post [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **MacroPdf417** |
| static [Mailmark](./mailmark/) | Αντιπροσωπεύει τον κώδικα Royal Mail Mailmark barcode. |
| static [Matrix2of5](./matrix2of5/) | Αντιπροσωπεύει τον κώδικα Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **MaxiCode** |
| static [MicroPdf417](./micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **MicroPdf417** |
| static [MicroQR](./microqr/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **MicroQR Code** |
| static [MSI](./msi/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **MSI Plessey** |
| static [None](./none/) | Μη καθορισμένος τύπος κωδικοποίησης. |
| static [OneCode](./onecode/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode USPS **OneCode** |
| static [OPC](./opc/) | Αντιπροσωπεύει τον κώδικα OPC (Optical Product Code) Barcode, επίσης γνωστό ως VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Αντιπροσωπεύει τον κώδικα Patch code barcode |
| static [Pdf417](./pdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Pdf417** |
| static [Pharmacode](./pharmacode/) | Αντιπροσωπεύει τον κώδικα Pharmacode barcode. |
| static [Planet](./planet/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Planet** |
| static [Postnet](./postnet/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Postnet** |
| static [PZN](./pzn/) | Αντιπροσωπεύει τον κώδικα PZN. Αυτή η συμβολική αναπαράσταση είναι επίσης γνωστή ως Pharmacy central number, Pharmazentralnummer. Υποστηρίζονται τα PZN7 και PZN8. Το PZN7 δημιουργείται από 6 ή λιγότερα ψηφία, όπως "123456". Το PZN8 δημιουργείται από 7 ή περισσότερα ψηφία, όπως "1234567". Το παρεχόμενο τελευταίο ψηφίο ελέγχου αγνοείται και δημιουργείται από τη μηχανή barcode. |
| static [QR](./qr/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **QR Code** |
| static [RectMicroQR](./rectmicroqr/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Αντιπροσωπεύει τον κώδικα RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) χρησιμοποιείται για την αυτοματοποιημένη διαδικασία ταξινόμησης αλληλογραφίας στο Ηνωμένο Βασίλειο. |
| static [SCC14](./scc14/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **SCC14** |
| static [SingaporePost](./singaporepost/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Singapore Post Barcode** |
| static [SSCC18](./sscc18/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **SSCC18** |
| static [Standard2of5](./standard2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Standard 2 of 5** |
| static [SwissPostParcel](./swisspostparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **Swiss Post Parcel Barcode**. Υποστηριζόμενοι τύποι: Ταχυδρομείο εντός χώρας, Διεθνές ταχυδρομείο, Πρόσθετες υπηρεσίες (νέο) |
| static [UPCA](./upca/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **UPC-A** |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **UPC coupon with GS1-128 Extended Code**. Παράδειγμα της εισαγόμενης συμβολοσειράς: BarcodeGenerator.Codetext = "514141100906(8102)03", όπου το τμήμα UPCA είναι "514141100906", το τμήμα GS1Code128 είναι (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **UPC coupon with GS1 DataBar addition**. Παράδειγμα της εισαγόμενης συμβολοσειράς: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", όπου το τμήμα UPCA είναι "514141100906", το τμήμα Databar είναι "(8110)106141416543213500110000310123196000". Για να αλλάξετε τη λεζάντα, χρησιμοποιήστε Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Καθορίζει ότι τα δεδομένα πρέπει να κωδικοποιηθούν με προδιαγραφή barcode **UPC-E** |
| static [VIN](./vin/) | Αναπαριστά το barcode VIN (Vehicle Identification Number). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
