---
title: "Aspose::BarCode::Generation::BarcodeParameters κλάση"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::BarcodeParameters κλάση. Παράμετροι δημιουργίας barcode σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Παράμετροι δημιουργίας barcode.

```cpp
class BarcodeParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | Παράμετροι barcode του AustralianPost. |
| [get_Aztec](./get_aztec/)() const | Παράμετροι Aztec. |
| [get_BarColor](./get_barcolor/)() const | Χρώμα γραμμών. Προεπιλεγμένη τιμή: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Ύψος των γραμμών των 1D barcode σε τιμή [Unit](../unit/). Αγνοείται εάν η ιδιότητα [BaseGenerationParameters::AutoSizeMode](../) έχει οριστεί σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Λαμβάνει ή ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση. Προεπιλεγμένη τιμή: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Πάντα να εμφανίζεται το ψηφίο ελέγχου στο κείμενο αναγνώσιμο από άνθρωπο για τους κωδικούς γραμμής Code128 και GS1Code128. |
| [get_Codabar](./get_codabar/)() const | Παράμετροι Codabar. |
| [get_Codablock](./get_codablock/)() const | Παράμετροι Codablock. |
| [get_Code128](./get_code128/)() const | Παράμετροι Code128. |
| [get_Code16K](./get_code16k/)() const | Παράμετροι Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Παράμετροι Codetext. |
| [get_Coupon](./get_coupon/)() const | Παράμετροι κουπονιού. Χρησιμοποιείται για UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Παράμετροι Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Παράμετροι DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Παράμετροι DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Λαμβάνει μια τιμή που υποδεικνύει αν οι γραμμές είναι γεμισμένες. Μόνο για 1D κωδικούς γραμμής. Προεπιλεγμένη τιμή: true. |
| [get_GS1](./get_gs1/)() const | Παράμετροι GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | Παράμετροι του GS1 Composite Bar. |
| [get_HanXin](./get_hanxin/)() const | Παράμετροι του HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Παράμετροι ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Παράμετροι MaxiCode. |
| [get_Padding](./get_padding/)() const | Περιθώρια κωδικού γραμμής. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Παράμετροι PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | Παράμετροι PDF417. |
| [get_Postal](./get_postal/)() const | Παράμετροι ταχυδρομείου. Χρησιμοποιούνται για Postnet, Planet. |
| [get_QR](./get_qr/)() const | Παράμετροι QR, MicroQR και RectMicroQR. |
| [get_Supplement](./get_supplement/)() const | Παράμετροι συμπλήρωσης. Χρησιμοποιούνται για Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Μόνο για 1D κωδικούς γραμμής. Εάν το codetext είναι εσφαλμένο και η τιμή οριστεί σε true - θα ριχθεί εξαίρεση. Διαφορετικά το codetext θα διορθωθεί ώστε να ταιριάζει με την προδιαγραφή του κωδικού γραμμής. Η εξαίρεση θα ριχθεί πάντα για: τη συμβολή Databar εάν το codetext είναι εσφαλμένο. Η εξαίρεση δεν θα ριχθεί ποτέ για: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, τη συμβολή Code128 εάν το codetext είναι εσφαλμένο. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του [BarCode](../../aspose.barcode/). Η αύξηση αυτού θα αυξήσει το συνολικό πλάτος της εικόνας του κωδικού γραμμής. Αγνοείται εάν η ιδιότητα [BaseGenerationParameters::AutoSizeMode](../) οριστεί σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Χρώμα γραμμών. Προεπιλεγμένη τιμή: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Ύψος των γραμμών των 1D barcode σε τιμή [Unit](../unit/). Αγνοείται εάν η ιδιότητα [BaseGenerationParameters::AutoSizeMode](../) έχει οριστεί σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Λαμβάνει ή ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελάνης κατά την εκτύπωση. Προεπιλεγμένη τιμή: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Πάντα να εμφανίζεται το ψηφίο ελέγχου στο κείμενο αναγνώσιμο από άνθρωπο για τους κωδικούς γραμμής Code128 και GS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | Ορίζει μια τιμή που υποδεικνύει αν οι γραμμές είναι γεμισμένες. Μόνο για 1D κωδικούς γραμμής. Προεπιλεγμένη τιμή: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | Παράμετροι του GS1 Composite Bar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Μόνο για 1D κωδικούς γραμμής. Εάν το codetext είναι εσφαλμένο και η τιμή οριστεί σε true - θα ριχθεί εξαίρεση. Διαφορετικά το codetext θα διορθωθεί ώστε να ταιριάζει με την προδιαγραφή του κωδικού γραμμής. Η εξαίρεση θα ριχθεί πάντα για: τη συμβολή Databar εάν το codetext είναι εσφαλμένο. Η εξαίρεση δεν θα ριχθεί ποτέ για: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, τη συμβολή Code128 εάν το codetext είναι εσφαλμένο. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του [BarCode](../../aspose.barcode/). Η αύξηση αυτού θα αυξήσει το συνολικό πλάτος της εικόνας του κωδικού γραμμής. Αγνοείται εάν η ιδιότητα [BaseGenerationParameters::AutoSizeMode](../) οριστεί σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
