---
title: "Enum DataMatrixEncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. Le mode d'encodage des encodeurs DataMatrix est par défaut Auto."
type: docs
weight: 1200
url: /fr/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Mode d'encodage de l'encodeur DataMatrix, par défaut sur Auto

```csharp
public enum DataMatrixEncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré-encodés dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. |
| ASCII | `1` | Encode un caractère alphanumérique ou deux caractères numériques par octet |
| C40 | `8` | Utilise l'encodage C40. Encode les caractères alphanumériques majuscules, minuscules et les caractères spéciaux |
| Text | `9` | Utilise l'encodage Text. Encode les caractères alphanumériques minuscules, majuscules et les caractères spéciaux |
| EDIFACT | `10` | Utilise l'encodage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreuses marques de ponctuation, mais ne prend pas en charge les lettres minuscules. |
| ANSIX12 | `11` | Utilise l'encodage ANSI X12. |
| Extended | `13` | Le mode ExtendedCodetext permet de changer manuellement les schémas d'encodage et les encodages ECI dans le codetext. |
| Base256 | `14` | Encode des valeurs de 8 bits |
| Binary | `15` | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | `16` | En mode ECI, le message complet est ré-encodé dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. Veuillez noter que certains anciens scanners (avant 2006) peuvent ne pas prendre en charge ce mode. |

## Exemples

Cet exemple montre comment créer du codetext en mode Étendu.

```csharp
[C#]
//Mode Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Mode Octets
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Mode codetext Étendu
//créer du codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


