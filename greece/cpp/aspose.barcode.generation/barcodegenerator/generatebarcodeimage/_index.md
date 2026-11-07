---
title: "μέθοδος"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Δημιουργήστε την εικόνα barcode με τις τρέχουσες ρυθμίσεις σε C++."
type: docs
weight: 800
url: /el/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Δημιουργήστε την εικόνα barcode σύμφωνα με τις τρέχουσες ρυθμίσεις.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Εικόνα barcode. Δείτε το [Bitmap](../).
## Σχόλια



Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Δείτε επίσης

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
