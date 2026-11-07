---
title: "Aspose::BarCode::Generation::BaseGenerationParameters κλάση"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters κλάση. Παράμετροι δημιουργίας εικόνας barcode σε C++."
type: docs
weight: 700
url: /el/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Παράμετροι δημιουργίας εικόνας barcode.

```cpp
class BaseGenerationParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. Προεπιλεγμένη τιμή: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Χρώμα φόντου της εικόνας barcode. Προεπιλεγμένη τιμή: Color.White. Δείτε το [Color](../). |
| [get_Barcode](./get_barcode/)() const | Αποκτά το [BarcodeParameters](../barcodeparameters/) που περιέχει όλες τις ιδιότητες του barcode. |
| [get_Border](./get_border/)() const | Αποκτά το [BorderParameters](../borderparameters/) που περιέχει όλες τις ιδιότητες διαμόρφωσης για το περίγραμμα του barcode. |
| [get_CaptionAbove](./get_captionabove/)() const | Λεζάντα Πάνω από την εικόνα [BarCode](../../aspose.barcode/). Δείτε το [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Λεζάντα Κάτω από την εικόνα [BarCode](../../aspose.barcode/). Δείτε το [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Παράμετροι εικόνας. Δείτε το [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Ύψος εικόνας [BarCode](../../aspose.barcode/) όταν η ιδιότητα [AutoSizeMode](../autosizemode/) ορίζεται σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Πλάτος εικόνας [BarCode](../../aspose.barcode/) όταν η ιδιότητα [AutoSizeMode](../autosizemode/) ορίζεται σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Λαμβάνει την ανάλυση της εικόνας [BarCode](../../aspose.barcode/). Μία τιμή για και τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Γωνία περιστροφής εικόνας [BarCode](../../aspose.barcode/), μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. Προεπιλεγμένη τιμή: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Χρώμα φόντου της εικόνας barcode. Προεπιλεγμένη τιμή: Color.White. Δείτε το [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Ύψος εικόνας [BarCode](../../aspose.barcode/) όταν η ιδιότητα [AutoSizeMode](../autosizemode/) ορίζεται σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Πλάτος εικόνας [BarCode](../../aspose.barcode/) όταν η ιδιότητα [AutoSizeMode](../autosizemode/) ορίζεται σε [AutoSizeMode.Nearest](../autosizemode/) ή [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Ορίζει την ανάλυση της εικόνας [BarCode](../../aspose.barcode/). Μία τιμή για και τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Γωνία περιστροφής εικόνας [BarCode](../../aspose.barcode/), μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
