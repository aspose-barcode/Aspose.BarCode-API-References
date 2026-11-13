---
title: "BarcodeParameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Παράμετροι δημιουργίας barcode.

Ο τύπος BarcodeParameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| x_dimension | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode.<br/>            Η αύξηση αυτού θα αυξήσει το συνολικό πλάτος της εικόνας barcode.<br/>            Αγνοείται εάν η ιδιότητα [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| bar_height | Ύψος των γραμμών των 1D barcode σε τιμή [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Αγνοείται εάν η ιδιότητα [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| bar_color | Χρώμα γραμμών.<br/>            Προεπιλεγμένη τιμή: Color.Black. |
| padding | Περιθώρια barcode.<br/>            Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Πάντα να εμφανίζεται το ψηφίο ελέγχου στο κείμενο αναγνώσιμο από άνθρωπο για τα barcode Code128 και GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Ισχύει μόνο για 1D barcode.<br/>            Εάν το κείμενο κώδικα είναι εσφαλμένο και η τιμή οριστεί σε true - θα ριχθεί εξαίρεση. Διαφορετικά το κείμενο κώδικα θα διορθωθεί ώστε να ταιριάζει με τις προδιαγραφές του barcode.<br/>            Η εξαίρεση θα ριχθεί πάντα για: τη συμβολική Databar εάν το κείμενο κώδικα είναι εσφαλμένο.<br/>            Η εξαίρεση δεν θα ριχθεί ποτέ για: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, τη συμβολική Code128 εάν το κείμενο κώδικα είναι εσφαλμένο. |
| wide_narrow_ratio | Αναλογία πλατών προς στενές γραμμές.<br/>            Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο πλατιές από τις στενές.<br/>            Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| code_text_parameters | Παράμετροι Codetext. |
| filled_bars | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμιστές.<br/>            Ισχύει μόνο για 1D barcode.<br/>            Προεπιλεγμένη τιμή: true. |
| bar_width_reduction | Λαμβάνει ή ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης της μελάνης κατά την εκτύπωση.<br/>            Προεπιλεγμένη τιμή: 0 |
| postal | Παράμετροι ταχυδρομείου. Χρησιμοποιείται για Postnet, Planet. |
| patch_code | Παράμετροι PatchCode. |
| australian_post | Παράμετροι barcode AustralianPost. |
| data_bar | Παράμετροι Databar. |
| gs1_composite_bar | GS1 Composite Bar παράμετροι. |
| codablock | Παράμετροι Codablock. |
| data_matrix | Παράμετροι DataMatrix. |
| code_16k | Παράμετροι Code16K. |
| dot_code | Παράμετροι DotCode. |
| itf | Παράμετροι ITF. |
| pdf417 | PDF417 παράμετροι. |
| qr | QR, MicroQR και RectMicroQR παράμετροι. |
| supplement | Παράμετροι συμπληρώματος. Χρησιμοποιείται για Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Παράμετροι MaxiCode. |
| aztec | Παράμετροι Aztec. |
| code128 | Παράμετροι Code128. |
| codabar | Παράμετροι Codabar. |
| coupon | Παράμετροι κουπονιού. Χρησιμοποιείται για UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | HanXin παράμετροι. |
| gs1 | Παράμετροι GS1. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

