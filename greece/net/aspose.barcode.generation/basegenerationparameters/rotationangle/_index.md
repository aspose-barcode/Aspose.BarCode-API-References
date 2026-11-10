---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BaseGenerationParameters ιδιότητα. Γωνία περιστροφής της εικόνας BarCode μετρημένη σε μοίρες π.χ. RotationAngle 0 ή RotationAngle 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90 180 270 ή 0, μπορεί να αυξήσει τη δυσκολία για τον σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή 0"
type: docs
weight: 110
url: /el/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0.

```csharp
public float RotationAngle { get; set; }
```

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα BarCode.

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
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


