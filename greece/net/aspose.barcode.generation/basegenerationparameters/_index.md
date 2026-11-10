---
title: "Κλάση BaseGenerationParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.BaseGenerationParameters. Παράμετροι δημιουργίας εικόνας barcode"
type: docs
weight: 1030
url: /el/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Παράμετροι δημιουργίας εικόνας barcode.

```csharp
public class BaseGenerationParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. Προεπιλεγμένη τιμή: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Χρώμα φόντου της εικόνας barcode. Προεπιλεγμένη τιμή: Color.White. Δείτε το Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Αποκτά το [`BarcodeParameters`](../barcodeparameters/) που περιέχει όλες τις ιδιότητες του barcode. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Αποκτά το [`BorderParameters`](../borderparameters/) που περιέχει όλες τις ιδιότητες διαμόρφωσης για το περίγραμμα του barcode. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | Λεζάντα πάνω από την εικόνα BarCode. Δείτε το [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | Λεζάντα κάτω από την εικόνα BarCode. Δείτε το [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Παράμετροι εικόνας. Δείτε το [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | Ύψος εικόνας BarCode όταν η ιδιότητα [`AutoSizeMode`](./autosizemode/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | Πλάτος εικόνας BarCode όταν η ιδιότητα [`AutoSizeMode`](./autosizemode/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση της εικόνας BarCode. Μία τιμή και για τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται λειτουργία anti-aliasing για την απόδοση της εικόνας |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


