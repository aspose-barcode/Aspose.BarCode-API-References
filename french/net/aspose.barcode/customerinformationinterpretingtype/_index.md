---
title: "Énumération CustomerInformationInterpretingType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.CustomerInformationInterpretingType. Définit le type d'interprétation CTable, NTable ou Autre des informations client pour le code-barres AustralianPost"
type: docs
weight: 910
url: /fr/net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

Définit le type d'interprétation (CTable, NTable ou Autre) des informations client pour le code-barres AustralianPost.

```csharp
public enum CustomerInformationInterpretingType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| CTable | `0` | Utilisez CTable pour interpréter les informations client. Autorise A..Z, a..z, 1..9, l'espace et le signe #. |
| NTable | `1` | Utilisez NTable pour interpréter les informations client. Autorise les chiffres. |
| Other | `2` | Ne pas interpréter les informations client. Autorise uniquement le symbole 0, 1, 2 ou 3. |

## Exemples

Ces exemples montrent comment générer et reconnaître le code-barres Australia Post

```csharp
[C#]
//Cet exemple montre comment générer et reconnaître le code-barres Australia Post avec le type d'interprétation CTable.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//Cet exemple montre comment générer et reconnaître le code-barres Australia Post sans type d'interprétation client.
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

### Voir aussi

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


