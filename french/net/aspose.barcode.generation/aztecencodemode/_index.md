---
title: "Enum AztecEncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Enum Aspose.BarCode.Generation.AztecEncodeMode. Mode d'encodage pour les codes-barres Aztec"
type: docs
weight: 940
url: /fr/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Mode d'encodage pour les codes-barres Aztec.

```csharp
public enum AztecEncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré-encodés dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. |
| Extended | `3` | Mode étendu qui prend en charge plusieurs modes ECI. |
| Binary | `4` | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | `5` | En mode ECI, le message complet est ré-encodé dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. Veuillez noter que certains anciens scanners (avant 2006) peuvent ne pas prendre en charge ce mode. |

## Exemples

```csharp
[C#]
//Mode Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Mode Étendu
//créer du codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


