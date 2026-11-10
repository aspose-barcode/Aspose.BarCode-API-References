---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété QrParameters. Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode octet pour les codes-barres QR et RectMicroQR"
type: docs
weight: 30
url: /fr/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR.

Si false, les séparateurs GS1 peuvent être encodés comme '%' en mode Alphanumérique selon la spécification QR.

Si true, les séparateurs de groupe GS1 sont encodés en mode Octet comme le caractère 0x1D, et les caractères '%' sont également encodés en mode Octet pour les préserver en tant que données.

Cette option peut améliorer la compatibilité avec les décodeurs qui attendent des séparateurs de groupe GS1 au niveau octet et empêche les caractères de données '%' d'être interprétés comme des séparateurs GS1.

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### Voir aussi

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


