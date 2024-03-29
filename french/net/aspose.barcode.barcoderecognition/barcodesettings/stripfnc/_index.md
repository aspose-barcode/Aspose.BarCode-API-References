---
title: StripFNC
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Supprimer les caractères FNC1 FNC2 FNC3 du texte de code. La valeur par défaut est false.
type: docs
weight: 40
url: /fr/net/aspose.barcode.barcoderecognition/barcodesettings/stripfnc/
---
## BarcodeSettings.StripFNC property

Supprimer les caractères FNC1, FNC2, FNC3 du texte de code. La valeur par défaut est false.

```csharp
public bool StripFNC { get; set; }
```

### Valeur de la propriété

Supprimez les caractères FNC1, FNC2, FNC3 du texte de code. La valeur par défaut est faux.

### Exemples

Cet exemple montre comment supprimer les caractères FNC

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC désactivé
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC activé
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC désactivé
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC activé
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir également

* class [BarcodeSettings](../../barcodesettings)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodesettings)
* Assemblée [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
