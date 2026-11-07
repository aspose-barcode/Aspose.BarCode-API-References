---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType κλάση"
linktitle: "DecodeType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType κλάση. Καθορίζει τον τύπο του barcode για ανάγνωση σε C++."
type: docs
weight: 1600
url: /el/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Καθορίστε τον τύπο του barcode για ανάγνωση.

```cpp
class DecodeType
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Λαμβάνει έναν πίνακα που αντιπροσωπεύει AllSupportedTypes |
| static [GetNames](./getnames/)() | Ανακτά έναν πίνακα με τα ονόματα των τύπων αποκωδικοποίησης. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Καθορίζει εάν ο καθορισμένος [BaseDecodeType](../basedecodetype/) περιέχει οποιαδήποτε 1D συμβολική γραμμωτού κώδικα |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Καθορίζει εάν ο καθορισμένος [BaseDecodeType](../basedecodetype/) περιέχει οποιαδήποτε 2D συμβολική γραμμωτού κώδικα |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Καθορίζει εάν ο καθορισμένος [BaseDecodeType](../basedecodetype/) περιέχει οποιαδήποτε ταχυδρομική συμβολική γραμμωτού κώδικα |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../singledecodetype/) σε παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Καθορίστε τα σύνολα σάρωσης με βάση τα barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../singledecodetype/) σε παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [MultiDecodeType](../multidecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις διαθέσιμες συμβολές |
| static [AustralianPosteParcel](./australianposteparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Australian Post Domestic eParcel Barcode** |
| static [AustraliaPost](./australiapost/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Australia Post** |
| static [Aztec](./aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Aztec** |
| static [Codabar](./codabar/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CODABAR** |
| static [CodablockF](./codablockf/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CodablockF** |
| static [Code11](./code11/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CODE 11** |
| static [Code128](./code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CODE 128** |
| static [Code16K](./code16k/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SCode16K** |
| static [Code32](./code32/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Code32** |
| static [Code39](./code39/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Code 39** βασικού συνόλου χαρακτήρων: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Code 39** πλήρους συνόλου χαρακτήρων ASCII: ISO/IEC 16388 |
| static [Code93](./code93/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CODE 93** |
| static [CompactPdf417](./compactpdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **CompactPdf417** (Pdf417Truncated) |
| static [DatabarExpanded](./databarexpanded/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar expanded** |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar expanded stacked** |
| static [DatabarLimited](./databarlimited/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar limited** |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar omni-directional** |
| static [DatabarStacked](./databarstacked/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar stacked** |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar stacked omni-directional** |
| static [DatabarTruncated](./databartruncated/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **GS1 Databar truncated** |
| static [DataLogic2of5](./datalogic2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **DataLogic 2 of 5** προδιαγραφή barcode |
| static [DataMatrix](./datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** συμβολική barcode |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **DeutschePost Ident code** προδιαγραφή barcode |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **DeutschePost Leit code** προδιαγραφή barcode |
| static [DotCode](./dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **DotCode** προδιαγραφή barcode |
| static [DutchKIX](./dutchkix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **DotCode** προδιαγραφή barcode |
| static [EAN13](./ean13/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **EAN-13** προδιαγραφή barcode |
| static [EAN14](./ean14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **EAN14** προδιαγραφή barcode |
| static [EAN8](./ean8/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **EAN-8** προδιαγραφή barcode |
| static [GS1Aztec](./gs1aztec/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 Aztec** προδιαγραφή barcode |
| static [GS1Code128](./gs1code128/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 CODE 128** προδιαγραφή barcode |
| static [GS1CompositeBar](./gs1compositebar/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 Composite Bar** προδιαγραφή barcode |
| static [GS1DataMatrix](./gs1datamatrix/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1DataMatrix** συμβολική barcode |
| static [GS1DotCode](./gs1dotcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 DotCode** προδιαγραφή barcode |
| static [GS1HanXin](./gs1hanxin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 Han Xin Code** προδιαγραφή barcode |
| static [GS1MicroPdf417](./gs1micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **MicroPdf417** προδιαγραφή barcode |
| static [GS1QR](./gs1qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** προδιαγραφή barcode |
| static [HanXin](./hanxin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **Han Xin Code** προδιαγραφή barcode |
| static [HIBCAztecLIC](./hibcazteclic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC LIC Aztec** προδιαγραφή barcode |
| static [HIBCAztecPAS](./hibcaztecpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC PAS Aztec** προδιαγραφή barcode |
| static [HIBCCode128LIC](./hibccode128lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC LIC Code128** προδιαγραφή barcode |
| static [HIBCCode128PAS](./hibccode128pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC PAS Code128** προδιαγραφή barcode |
| static [HIBCCode39LIC](./hibccode39lic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC LIC Code39** προδιαγραφή barcode |
| static [HIBCCode39PAS](./hibccode39pas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC PAS Code39** προδιαγραφή barcode |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** προδιαγραφή barcode |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** προδιαγραφή barcode |
| static [HIBCQRLIC](./hibcqrlic/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [HIBCQRPAS](./hibcqrpas/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** |
| static [IATA2of5](./iata2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **IATA 2 of 5**. Η IATA (International Air Transport Association) χρησιμοποιεί αυτό το barcode για τη διαχείριση του αεροπορικού φορτίου. |
| static [Interleaved2of5](./interleaved2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **INTERLEAVED 2 of 5** |
| static [ISBN](./isbn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISBN** |
| static [ISMN](./ismn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISMN** |
| static [ISSN](./issn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ISSN** |
| static [ItalianPost25](./italianpost25/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Italian Post 25** |
| static [ITF14](./itf14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ITF14** |
| static [ITF6](./itf6/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **ITF6** |
| static [JapanPost](./japanpost/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Japan Post** |
| static [MacroPdf417](./macropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MacroPdf417** |
| static [Mailmark](./mailmark/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Royal Mail Mailmark**. |
| static [Matrix2of5](./matrix2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Matrix 2 of 5** |
| static [MaxiCode](./maxicode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MaxiCode** |
| static [MicrE13B](./micre13b/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MICR E-13B** |
| static [MicroPdf417](./micropdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **MicroPdf417** προδιαγραφή barcode |
| static [MicroQR](./microqr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroQR Code** |
| static [MostCommonTypes](./mostcommontypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με τις πιο συχνά χρησιμοποιούμενες συμβολισμούς |
| static [MSI](./msi/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MSI Plessey** |
| static [None](./none/) | Μη καθορισμένος τύπος αποκωδικοποίησης. |
| static [OneCode](./onecode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode USPS **OneCode** |
| static [OPC](./opc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **OPC** |
| static [PatchCode](./patchcode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Patch code**. Η συμβολή barcode χρησιμοποιείται για αυτοματοποιημένη σάρωση |
| static [Pdf417](./pdf417/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **Pdf417** συμβολή barcode |
| static [Pharmacode](./pharmacode/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **Pharmacode** barcode. Αυτή η συμβολή είναι επίσης γνωστή ως Pharmaceutical Binary Code |
| static [Planet](./planet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Planet** |
| static [PostalTypes](./postaltypes/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις συμβολές barcode **1.5D Postal**, όπως **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Postnet** |
| static [PZN](./pzn/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **PZN**. Αυτή η συμβολή είναι επίσης γνωστή ως Pharma Zentral Nummer. Υποστηρίζονται τα PZN7 και PZN8. |
| static [QR](./qr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** |
| static [RectMicroQR](./rectmicroqr/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RectMicroQR (rMQR) Code** |
| static [RM4SCC](./rm4scc/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RM4SCC**. Το RM4SCC (Royal Mail 4-state Customer Code) χρησιμοποιείται για αυτοματοποιημένη διαδικασία ταξινόμησης αλληλογραφίας στο Ηνωμένο Βασίλειο. |
| static [SCC14](./scc14/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SCC14** |
| static [SSCC18](./sscc18/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SSCC18** |
| static [Standard2of5](./standard2of5/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Standard 2 of 5** |
| static [Supplement](./supplement/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Supplement(EAN2, EAN5)** |
| static [SwissPostParcel](./swisspostparcel/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Swiss Post Parcel Barcode** |
| static [Types1D](./types1d/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις συμβολές barcode **1D** |
| static [Types2D](./types2d/) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις συμβολές barcode **2D** |
| static [UPCA](./upca/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-A** |
| static [UPCE](./upce/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-E** |
| static [VIN](./vin/) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **VIN** (Vehicle Identification Number) |
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
