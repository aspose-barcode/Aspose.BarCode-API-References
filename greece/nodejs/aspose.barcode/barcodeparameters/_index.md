---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι δημιουργίας barcode."
type: docs
weight: 140
url: /el/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Παράμετροι δημιουργίας barcode.

```js
new BarcodeParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Παράμετροι γραμμωτού κώδικα AustralianPost. |
| [getAztec()](#getaztec) | Παράμετροι Aztec. |
| [getBarColor()](#getbarcolor) | Χρώμα γραμμών. |
| [getBarHeight()](#getbarheight) | Ύψος των γραμμών των 1D barcode σε τιμή μονάδας. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMo. |
| [getBarWidthReduction()](#getbarwidthreduction) | Λάβετε την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Πάντα εμφανίστε το ψηφίο ελέγχου στο κείμενο που διαβάζεται από άνθρωπο για τα barcode Code128 και GS1Code128. |
| [getCodabar()](#getcodabar) | Παράμετροι Codabar. |
| [getCodablock()](#getcodablock) | Παράμετροι Codablock. |
| [getCode16K()](#getcode16k) | Παράμετροι Code16K. |
| [getCode128()](#getcode128) | Παράμετροι Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Παράμετροι Codetext. |
| [getCoupon()](#getcoupon) | Παράμετροι Coupon. Χρησιμοποιείται για UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Παράμετροι Databar. |
| [getDataMatrix()](#getdatamatrix) | Παράμετροι DataMatrix. |
| [getDotCode()](#getdotcode) | Παράμετροι DotCode. |
| [getEnableEscape()](#getenableescape) | Υποδεικνύει εάν εξηγεί τον χαρακτήρα \"\\\" ως χαρακτήρα διαφυγής στην ιδιότητα CodeText. Χρησιμοποιείται για Pdf417, DataMatrix, C. |
| [getFilledBars()](#getfilledbars) | Λαμβάνει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Ισχύει μόνο για 1D barcode. Προεπιλεγμένη τιμή: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Παράμετροι GS1 Composite Bar. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το 1D codetext |
| [getHanXin()](#gethanxin) | Παράμετροι HanXin. |
| [getITF()](#getitf) | Παράμετροι ITF. |
| [getMaxiCode()](#getmaxicode) | Παράμετροι MaxiCode. |
| [getPadding()](#getpadding) | Περιθώρια barcode. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Παράμετροι PatchCode. |
| [getPdf417()](#getpdf417) | Παράμετροι PDF417. |
| [getPostal()](#getpostal) | Παράμετροι ταχυδρομείου. Χρησιμοποιείται για Postnet, Planet. |
| [getQR()](#getqr) | Παράμετροι QR. |
| [getSupplement()](#getsupplement) | Παράμετροι συμπλήρωσης. Χρησιμοποιείται για Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, |
| [getXDimension()](#getxdimension) | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτής θα αυξήσει ολόκληρο το barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία 1D barcode. Η προεπιλογή θεωρείται Yes για συμβολισμούς που πρέπει να περιέχουν έλεγχο, ως N |
| [setBarColor(value)](#setbarcolor) | Χρώμα γραμμών. |
| [setBarHeight()](#setbarheight) | Ύψος των γραμμών των 1D barcode σε τιμή μονάδας. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMo. |
| [setBarWidthReduction()](#setbarwidthreduction) | Ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Πάντα εμφανίστε το ψηφίο ελέγχου στο κείμενο που διαβάζεται από άνθρωπο για τα barcode Code128 και GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία 1D barcode. Η προεπιλογή θεωρείται Yes για συμβολισμούς που πρέπει να περιέχουν έλεγχο, ως N |
| [setEnableEscape()](#setenableescape) | Υποδεικνύει εάν εξηγεί τον χαρακτήρα \"\\\" ως χαρακτήρα διαφυγής στην ιδιότητα CodeText. Χρησιμοποιείται για Pdf417, DataMatrix, C. |
| [setFilledBars()](#setfilledbars) | Ορίζει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Ισχύει μόνο για 1D barcode. Προεπιλεγμένη τιμή: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Παράμετροι GS1 Composite Bar. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το 1D codetext |
| [setPadding()](#setpadding) | Περιθώρια barcode. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, P |
| [setXDimension()](#setxdimension) | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτής θα αυξήσει ολόκληρο το barcode i |

### getAustralianPost() {#getaustralianpost}

Παράμετροι γραμμωτού κώδικα AustralianPost.

### getAztec() {#getaztec}

Παράμετροι Aztec.

### getBarColor() {#getbarcolor}

Χρώμα γραμμών.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Ύψος των γραμμών των 1D barcode σε τιμή μονάδας. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Λάβετε την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Πάντα εμφανίστε το ψηφίο ελέγχου στο κείμενο που διαβάζεται από άνθρωπο για τα barcode Code128 και GS1Code128.

### getCodabar() {#getcodabar}

Παράμετροι Codabar.

### getCodablock() {#getcodablock}

Παράμετροι Codablock.

### getCode16K() {#getcode16k}

Παράμετροι Code16K.

### getCode128() {#getcode128}

Παράμετροι Code128.

### getCodeTextParameters() {#getcodetextparameters}

Παράμετροι Codetext.

### getCoupon() {#getcoupon}

Παράμετροι Coupon. Χρησιμοποιείται για UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Παράμετροι Databar.

### getDataMatrix() {#getdatamatrix}

Παράμετροι DataMatrix.

### getDotCode() {#getdotcode}

Παράμετροι DotCode.

### getEnableEscape() {#getenableescape}

Υποδεικνύει εάν εξηγεί τον χαρακτήρα \"\\\" ως χαρακτήρα διαφυγής στην ιδιότητα CodeText. Χρησιμοποιείται για Pdf417, DataMatrix, Code128 μόνο. Εάν το EnableEscape είναι true, το \"\\\" θα εξηγηθεί ως ειδικός χαρακτήρας διαφυγής. Διαφορετικά, το \"\\\" λειτουργεί ως κανονικοί χαρακτήρες. Το Aspose.BarCode υποστηρίζει την εισαγωγή δεκαδικού κώδικα ascii και μνημονικού για χαρακτήρες ελέγχου ASCII. Για παράδειγμα, \013 και \\\\CR αντιστοιχούν στο CR.

### getFilledBars() {#getfilledbars}

Λαμβάνει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Ισχύει μόνο για 1D barcode. Προεπιλεγμένη τιμή: true.

### getGS1CompositeBar() {#getgs1compositebar}

Παράμετροι GS1 Composite Bar. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το 1D codetext και το 2D codetext χωρίζονται με το σύμβολο '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

Παράμετροι HanXin.

### getITF() {#getitf}

Παράμετροι ITF.

### getMaxiCode() {#getmaxicode}

Παράμετροι MaxiCode.

### getPadding() {#getpadding}

Περιθώρια barcode. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Παράμετροι PatchCode.

### getPdf417() {#getpdf417}

Παράμετροι PDF417.

### getPostal() {#getpostal}

Παράμετροι ταχυδρομείου. Χρησιμοποιείται για Postnet, Planet.

### getQR() {#getqr}

Παράμετροι QR.

### getSupplement() {#getsupplement}

Παράμετροι συμπλήρωσης. Χρησιμοποιείται για Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Η τιμή της παραμέτρου WideNarrowRatio είναι μικρότερη ή ίση με 0.

### getXDimension() {#getxdimension}

Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτής θα αυξήσει το συνολικό πλάτος της εικόνας barcode. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Ενεργοποιήστε το άθροισμα ελέγχου κατά τη δημιουργία 1D barcode. Η προεπιλογή θεωρείται Ναι για τις συμβολές που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι δυνατό μόνο. Το άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Το άθροισμα ελέγχου χρησιμοποιείται πάντα: Υπόλοιπες συμβολές

### setBarColor(value) {#setbarcolor}

Χρώμα γραμμών.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | String | για το χρώμα γραμμής Η προεπιλεγμένη τιμή: #000000. |

### setBarHeight() {#setbarheight}

Ύψος των γραμμών των 1D barcode σε τιμή μονάδας. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Πάντα εμφανίστε το ψηφίο ελέγχου στο κείμενο που διαβάζεται από άνθρωπο για τα barcode Code128 και GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Ενεργοποιήστε το άθροισμα ελέγχου κατά τη δημιουργία 1D barcode. Η προεπιλογή θεωρείται Ναι για τις συμβολές που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι δυνατό μόνο. Το άθροισμα ελέγχου είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Το άθροισμα ελέγχου χρησιμοποιείται πάντα: Υπόλοιπες συμβολές

### setEnableEscape() {#setenableescape}

Δείχνει εάν εξηγεί τον χαρακτήρα \"\\\" ως χαρακτήρα διαφυγής στην ιδιότητα CodeText. Χρησιμοποιείται μόνο για Pdf417, DataMatrix, Code128. Εάν το EnableEscape είναι true, το \"\\\" θα εξηγηθεί ως ειδικός χαρακτήρας διαφυγής. Διαφορετικά, το \"\\\" λειτουργεί ως κανονικοί χαρακτήρες. Το Aspose.BarCode υποστηρίζει τον δεκαδικό κώδικα ascii και μνημονικό για χαρακτήρες ελέγχου ASCII. Για παράδειγμα, \\013 και \\\\CR αντιπροσωπεύουν το CR.

### setFilledBars() {#setfilledbars}

Ορίζει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Ισχύει μόνο για 1D barcode. Προεπιλεγμένη τιμή: true.

### setGS1CompositeBar() {#setgs1compositebar}

Παράμετροι GS1 Composite Bar. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το 1D codetext και το 2D codetext χωρίζονται με το σύμβολο '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Περιθώρια barcode. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Αναλογία πλατών γραμμών προς στενές γραμμών. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Η τιμή της παραμέτρου WideNarrowRatio είναι μικρότερη ή ίση με 0.

### setXDimension() {#setxdimension}

Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτής θα αυξήσει το συνολικό πλάτος της εικόνας barcode. Αγνοείται εάν η ιδιότητα AutoSizeMode οριστεί σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
