---
title: "BarcodeSettings.ChecksumValidation"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarcodeSettings. Active la validation du checksum pendant la reconnaissance pour les codes-barres 1D et postaux"
type: docs
weight: 30
url: /fr/net/aspose.barcode.barcoderecognition/barcodesettings/checksumvalidation/
---
## BarcodeSettings.ChecksumValidation property

Active la validation de la somme de contrôle pendant la reconnaissance des codes‑à‑barres 1D et postaux.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que.

Checksum jamais utilisé : Codabar, PatchCode, Pharmacode, DataLogic2of5

La somme de contrôle est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Somme de contrôle toujours utilisée : le reste des symbologies

```csharp
public ChecksumValidation ChecksumValidation { get; set; }
```

### Property Value

Active la validation de la somme de contrôle pendant la reconnaissance des codes‑à‑barres 1D et postaux.

## Exemples

Cet exemple montre l'influence de ChecksumValidation sur la qualité et les résultats de la reconnaissance

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //somme de contrôle désactivée
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //somme de contrôle activée
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Voir aussi

* enum [ChecksumValidation](../../checksumvalidation/)
* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


