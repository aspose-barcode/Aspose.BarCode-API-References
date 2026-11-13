---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Παράμετροι δημιουργίας εικόνας barcode.

Ο τύπος BaseGenerationParameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| use_anti_alias | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας |
| back_color | Χρώμα φόντου της εικόνας barcode.<br/>            Προεπιλεγμένη τιμή: Color.White.<br/>            Δείτε [Color](/barcode/python-net/aspose.drawing/color/). |
| ανάλυση | Λαμβάνει ή ορίζει την ανάλυση της εικόνας BarCode.<br/>            Μία τιμή και για τις δύο διαστάσεις.<br/>            Προεπιλεγμένη τιμή: 96 dpi. |
| rotation_angle | Γωνία περιστροφής της εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή.<br/>            Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα.<br/>            Προεπιλεγμένη τιμή: 0. |
| caption_above | Λεζάντα πάνω από την εικόνα BarCode. Δείτε [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Λεζάντα κάτω από την εικόνα BarCode. Δείτε [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Παράμετροι εικόνας. Δείτε [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης.<br/>            Προεπιλεγμένη τιμή: AutoSizeMode.None. |
| image_height | Ύψος εικόνας BarCode όταν η ιδιότητα [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| image_width | Πλάτος εικόνας BarCode όταν η ιδιότητα [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) ορίζεται σε AutoSizeMode.Nearest ή AutoSizeMode.Interpolation. |
| barcode | Αποκτά το [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) που περιέχει όλες τις ιδιότητες του barcode. |
| border | Αποκτά το [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) που περιέχει όλες τις ιδιότητες διαμόρφωσης για το περίγραμμα του barcode. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

