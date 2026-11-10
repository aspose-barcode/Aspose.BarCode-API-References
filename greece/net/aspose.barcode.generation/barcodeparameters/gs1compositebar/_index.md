---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeParameters ιδιότητα. GS1 Composite Bar παράμετροι"
type: docs
weight: 180
url: /el/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

Παράμετροι σύνθετης γραμμής GS1.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα GS1 Composite Bar. Σημειώστε ότι το 1D codetext και το 2D codetext χωρίζονται με το σύμβολο '&#x7C;'

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // Αναλογία διαστάσεων του 2D στοιχείου
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // Διάσταση X των στοιχείων 1D και 2D
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // Ύψος του στοιχείου 1D
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### Δείτε επίσης

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


