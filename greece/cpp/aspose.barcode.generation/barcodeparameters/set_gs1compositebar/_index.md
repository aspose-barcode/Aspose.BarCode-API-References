---
title: "μέθοδος"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Παράμετροι GS1 Composite Bar σε C++."
type: docs
weight: 2600
url: /el/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


Παράμετροι του GS1 Composite Bar.

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το κείμενο κώδικα 1D και 2D χωρίζονται με το σύμβολο '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Αναλογία διαστάσεων 2D στοιχείου
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // Διάσταση X των 1D και 2D στοιχείων
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Ύψος 1D στοιχείου
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Δείτε επίσης

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
