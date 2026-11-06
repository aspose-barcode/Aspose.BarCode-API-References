---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αυτό το πακέτο περιέχει εργαλεία για την αναγνώριση γραμμωτών/δισδιάστατων κωδίκων."
type: docs
weight: 11
url: /el/androidjava/com.aspose.barcode.barcoderecognition/
---

Αυτό το πακέτο περιέχει εργαλεία για την αναγνώριση γραμμωτών/δισδιάστατων κωδίκων.


## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Παράμετροι αποκωδικοποίησης AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Αποθηκεύει επεκταμένες παραμέτρους του αναγνωρισμένου barcode |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | Το BarCodeReader περιλαμβάνει μια εικόνα που μπορεί να περιέχει ένα ή περισσότερα barcodes, και στη συνέχεια μπορεί να εκτελέσει τη λειτουργία ReadBarCodes για την ανίχνευση των barcodes. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Γενική εξαίρεση που ρίχνεται από το BarCodeReader, κληρονομείται από το BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Αποθηκεύει δεδομένα του αναγνωρισμένου barcode όπως ο τύπος SingleDecodeType, η συμβολοσειρά codetext, η BarCodeRegionParameters περιοχή και άλλες παραμέτρους |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Οι κύριες παραμέτρους αποκωδικοποίησης BarCode. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Ρυθμίσεις ανιχνευτή Barcode. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Βασική κλάση για το MultiDecodeType και το SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Βασική κλάση για την αποθήκευση επεκταμένων παραμέτρων του αναγνωρισμένου barcode |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Αποθηκεύει πρόσθετες πληροφορίες Codabar του αναγνωρισμένου barcode |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Περιέχει τα δεδομένα του υποτύπου για barcode τύπου Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Αποθηκεύει πρόσθετες πληροφορίες DataBar του αναγνωρισμένου barcode BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DataMatrix |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Καθορίστε τον τύπο του barcode που θα διαβαστεί. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DotCode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode **GS1 Composite Bar** |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Αποθηκεύει πρόσθετες πληροφορίες MaxiCode του αναγνωρισμένου barcode |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Σύνθετος τύπος αποκωδικοποίησης. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode 1D, όπως ξεχωριστό κείμενο κώδικα και άθροισμα ελέγχου |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | Το ProcessorSettings επιτρέπει την αναγνώριση barcode με πολυνηματική βελτίωση της απόδοσης |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Αποθηκεύει ένα σύνολο από τέσσερα Point που αντιπροσωπεύουν μια περιοχή Quadrangle. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας της αναγνώρισης. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Αναπαριστά την εξαίρεση διακοπής αναγνώρισης που ρίχνεται όταν ξεπεραστεί το χρονικό όριο κατά τη διάρκεια της αναγνώρισης με BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Μονός τύπος αποκωδικοποίησης. |

## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Δημόσια διεπαφή για την αποκωδικοποίηση του πεδίου Customer Information Field που χρησιμοποιείται στη συμβολική AustraliaPost. |

## Απαριθμήσεις

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Περιέχει το επίπεδο εμπιστοσύνης της αναγνώρισης |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Περιέχει τύπους του υποσυνόλου Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Ορίζει τον τύπο ερμηνείας (C\_TABLE ή N\_TABLE) των πληροφοριών πελάτη για το AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Καθορίστε το μέγεθος της κλιμακωτής εικόνας |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
