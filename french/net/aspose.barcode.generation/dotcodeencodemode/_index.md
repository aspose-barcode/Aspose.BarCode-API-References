---
title: "Énumération DotCodeEncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.DotCodeEncodeMode. Mode d'encodage pour les codes-barres DotCode"
type: docs
weight: 1240
url: /fr/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Mode d'encodage pour les codes-barres DotCode.

```csharp
public enum DotCodeEncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré-encodés dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. |
| Binary | `3` | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | `4` | En mode ECI, le message complet est ré-encodé dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. Veuillez noter que certains anciens scanners (avant 2006) peuvent ne pas prendre en charge ce mode. |
| Extended | `5` | Mode étendu qui prend en charge plusieurs modes ECI. |

## Exemples

```csharp
[C#]
//Mode automatique avec macros
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Mode Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Mode Octets
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Mode codetext Étendu
//créer du codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


