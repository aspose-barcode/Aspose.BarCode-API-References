---
title: "μέθοδος"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν RotationAngle ΔΕΝ είναι ίση με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για τον σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0 σε C++."
type: docs
weight: 700
url: /el/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Δείτε επίσης

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
