---
title: RotationAngle
second_title: Aspose.BarCode για Αναφορά API .NET
description: Γωνία περιστροφής εικόνας BarCode μετρημένη σε μοίρες π.χ. Γωνία Περιστροφής  0 ή Γωνία Περιστροφής  360 σημαίνει ότι δεν υπάρχει περιστροφή. Εάν η γωνία περιστροφής ΔΕΝ ισούται με 90 180 270 ή 0 μπορεί να αυξήσει τη δυσκολία του σαρωτή να διαβάσει__x00 την εικόνα. Προεπιλεγμένη τιμή 0.
type: docs
weight: 100
url: /el/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. Γωνία Περιστροφής = 0 ή Γωνία Περιστροφής = 360 σημαίνει ότι δεν υπάρχει περιστροφή. Εάν η γωνία περιστροφής ΔΕΝ ισούται με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία του σαρωτή να διαβάσει__x00 την εικόνα. Προεπιλεγμένη τιμή: 0.

```csharp
public float RotationAngle { get; set; }
```

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα BarCode.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Δείτε επίσης

* class [BaseGenerationParameters](../)
* χώρος ονομάτων [Aspose.BarCode.Generation](../../basegenerationparameters/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
