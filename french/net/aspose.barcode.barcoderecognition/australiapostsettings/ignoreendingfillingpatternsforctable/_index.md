---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété AustraliaPostSettings. Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage avec la méthode CTable. La méthode d'encodage CTable ne comporte aucun espace dans la table d'encodage et la séquence 333 de motifs de remplissage est décodée comme la lettre z"
type: docs
weight: 30
url: /fr/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'information client lors du décodage selon la méthode CTable. La méthode d'encodage CTable n'a aucun vide dans la table d'encodage et la séquence "333" des motifs de remplissage est décodée comme la lettre "z".

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage lors du décodage avec la méthode CTable

## Exemples

Cet exemple montre comment générer et reconnaître le code-barres Australia Post avec le type d'interprétation CTable tout en ignorant les motifs de remplissage.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### Voir aussi

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


