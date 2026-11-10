---
title: "Énumération MaxiCodeEncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.MaxiCodeEncodeMode. Mode d'encodage pour les codes-barres MaxiCode"
type: docs
weight: 1460
url: /fr/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

Mode d'encodage pour les codes-barres MaxiCode.

```csharp
public enum MaxiCodeEncodeMode
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
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Mode Octets
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Mode codetext Étendu
//créer du codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


