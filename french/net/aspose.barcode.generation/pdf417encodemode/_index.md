---
title: "Enum Pdf417EncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Enum Aspose.BarCode.Generation.Pdf417EncodeMode. Mode d'encodage du code-barres Pdf417"
type: docs
weight: 1540
url: /fr/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Mode d'encodage du code-barres Pdf417

```csharp
public enum Pdf417EncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré-encodés dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. |
| Binary | `1` | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | `2` | En mode ECI, le message complet est ré-encodé dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. Veuillez noter que certains anciens scanners (avant 2006) peuvent ne pas prendre en charge ce mode. |
| Extended | `3` | Mode étendu qui prend en charge plusieurs modes ECI. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


