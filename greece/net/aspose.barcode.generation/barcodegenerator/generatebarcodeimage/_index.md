---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeGenerator μέθοδος. Δημιουργεί την εικόνα barcode με τις τρέχουσες ρυθμίσεις"
type: docs
weight: 80
url: /el/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Δημιουργεί την εικόνα barcode με τις τρέχουσες ρυθμίσεις.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Τιμή Επιστροφής

Εικόνα barcode. Δείτε το Bitmap.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Δείτε επίσης

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


