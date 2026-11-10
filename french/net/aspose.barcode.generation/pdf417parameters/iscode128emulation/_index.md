---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété Pdf417Parameters. Peut être utilisé uniquement avec MicroPdf417 et encode les modes d’émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128"
type: docs
weight: 60
url: /fr/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Exemples

Ces exemples montrent comment encoder les modes d’émulation Code 128 avec FNC1 en deuxième position et sans. De cette façon, MicroPdf417 peut être décodé comme un code‑barres Code 128

```csharp
[C#]
//Encode MicroPdf417 en mode d'émulation Code 128 avec FNC1 en deuxième position et indicateur d'application "a", mode 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encode MicroPdf417 en mode d'émulation Code 128 avec FNC1 en deuxième position et indicateur d'application "99", mode 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Encode MicroPdf417 en mode d'émulation Code 128, modes 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Voir aussi

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


