---
title: "BarCodeReader.ProcessorSettings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarCodeReader. Obtient les paramètres d'utilisation des cœurs du processeur"
type: docs
weight: 140
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Obtient les paramètres d'utilisation des cœurs du processeur.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Exemples

Cet exemple montre comment utiliser ProcessorSettings pour ajouter des performances multithread maximales

```csharp
[C#]
//cela permet d'utiliser tous les cœurs pour un appel unique à BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//cela permet d'utiliser le nombre actuel de cœurs
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Voir aussi

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


