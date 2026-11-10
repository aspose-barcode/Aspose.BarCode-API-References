---
title: "Κλάση FontUnit"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.FontUnit κλάση. Ορίζει μια συγκεκριμένη μορφή κειμένου που περιλαμβάνει το μέγεθος και τα χαρακτηριστικά της γραμματοσειράς, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value."
type: docs
weight: 1320
url: /el/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Ορίζει μια συγκεκριμένη μορφή κειμένου, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value.

```csharp
public sealed class FontUnit
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Αποκτά ή ορίζει το όνομα γραμματοσειράς αυτού του Font. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Αποκτά ή ορίζει το μέγεθος αυτού του FontUnit στην τιμή Unit. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Αποκτά ή ορίζει τις πληροφορίες στυλ για αυτό το FontUnit. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


