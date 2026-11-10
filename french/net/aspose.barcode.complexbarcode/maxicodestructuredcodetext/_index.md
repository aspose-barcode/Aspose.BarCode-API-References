---
title: "Classe MaxiCodeStructuredCodetext"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeStructuredCodetext class. Classe de base pour encoder et décoder le texte intégré dans le code MaxiCode pour les modes 2 et 3"
type: docs
weight: 740
url: /fr/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3.

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | Identifie le code pays à 3 chiffres. |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Obtient ou définit l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Obtient ou définit un mode d'encodage MaxiCode. Valeur par défaut : Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 symboles alphanumériques en mode 3. |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | Identifie le deuxième message du code-barres. |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | Identifie la catégorie de service à 3 chiffres. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `MaxiCodeStructuredCodetext` spécifiée. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Obtient le type de code-barres. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | Construit le texte du code |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Obtient le mode MaxiCode. |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | Initialise l'instance à partir du texte du code construit. |

## Exemples

Cet exemple montre comment décoder le texte brut MaxiCode en instance MaxiCodeStructuredCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

### Voir aussi

* class [MaxiCodeCodetext](../maxicodecodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


