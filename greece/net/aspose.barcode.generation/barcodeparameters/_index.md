---
title: "Κλάση BarcodeParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.BarcodeParameters κλάση. Παράμετροι δημιουργίας Barcode."
type: docs
weight: 1010
url: /el/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Παράμετροι δημιουργίας barcode.

```csharp
public class BarcodeParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | Παράμετροι barcode του AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Παράμετροι Aztec. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Χρώμα γραμμών. Προεπιλεγμένη τιμή: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Ύψος των γραμμών των 1D barcode σε τιμή [`Unit`](../unit/). Αγνοείται εάν η ιδιότητα [`AutoSizeMode`](../basegenerationparameters/autosizemode/) οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μείωσης των γραμμών που χρησιμοποιείται για την αντιστάθμιση της εξάπλωσης μελανιού κατά την εκτύπωση. Προεπιλεγμένη τιμή: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Πάντα να εμφανίζεται το ψηφίο ελέγχου στο κείμενο αναγνώσιμο από άνθρωπο για τους γραμμωτούς κώδικες Code128 και GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Παράμετροι Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Παράμετροι Codablock. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Παράμετροι Code128. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Παράμετροι Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Παράμετροι κειμένου κώδικα. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Παράμετροι Coupon. Χρησιμοποιείται για UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Παράμετροι Databar. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | Παράμετροι DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | Παράμετροι DotCode. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι γραμμές είναι γεμισμένες. Μόνο για 1D barcode. Προεπιλεγμένη τιμή: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | Παράμετροι GS1. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | Παράμετροι σύνθετης γραμμής GS1. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | Παράμετροι HanXin. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Ενεργοποίηση ελέγχου αθροίσματος κατά τη δημιουργία 1D barcodes. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | Παράμετροι ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | Παράμετροι MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Αποστάσεις padding του Barcode. Προεπιλεγμένη τιμή: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | Παράμετροι PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | Παράμετροι PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Παράμετροι ταχυδρομείου. Χρησιμοποιείται για Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | Παράμετροι QR, MicroQR και RectMicroQR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Παράμετροι συμπλήρωσης. Χρησιμοποιείται για Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Μόνο για 1D barcode. Εάν το codetext είναι εσφαλμένο και η τιμή οριστεί σε true - θα εξαχθεί εξαίρεση. Διαφορετικά το codetext θα διορθωθεί ώστε να ταιριάζει με τις προδιαγραφές του barcode. Η εξαίρεση θα εξαχθεί πάντα για: σύμβολο Databar εάν το codetext είναι εσφαλμένο. Η εξαίρεση δεν θα εξαχθεί ποτέ για: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 εάν το codetext είναι εσφαλμένο. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Αναλογία πλατών γραμμών προς στενές γραμμές. Προεπιλεγμένη τιμή: 3, δηλαδή οι πλατές γραμμές είναι 3 φορές πιο φαρδιές από τις στενές. Χρησιμοποιείται για ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | Η διάσταση x είναι το μικρότερο πλάτος της μονάδας των γραμμών ή κενών του BarCode. Η αύξηση αυτού θα αυξήσει το συνολικό πλάτος της εικόνας barcode. Αγνοείται εάν η ιδιότητα [`AutoSizeMode`](../basegenerationparameters/autosizemode/) οριστεί σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


