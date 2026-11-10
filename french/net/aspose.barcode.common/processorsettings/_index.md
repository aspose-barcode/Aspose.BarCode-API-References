---
title: "Classe ProcessorSettings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Common.ProcessorSettings. ProcessorSettings permet de reconnaître les codes-barres avec une amélioration multithread des performances"
type: docs
weight: 470
url: /fr/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings permet de reconnaître les codes-barres avec une amélioration des performances multithreadée

```csharp
public class ProcessorSettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Spécifiez le nombre maximal de threads supplémentaires pour exécuter le code en parallèle |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Est nécessaire pour utiliser tous les cœurs. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Spécifiez le nombre de cœurs à utiliser. Vous devez changer la propriété "UseAllCores" en "false". |

## Exemples

Cet exemple montre comment utiliser ProcessorSettings pour ajouter des performances multithread maximales

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//cela permet d'utiliser tous les cœurs pour un appel unique à BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//cela permet d'utiliser le nombre actuel de cœurs
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
Dim workerThreads As Integer = Environment.ProcessorCount * 2
Dim portThreads As Integer = Environment.ProcessorCount * 2
System.Threading.ThreadPool.GetMinThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads)
System.Threading.ThreadPool.GetMaxThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads)
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2

'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Voir aussi

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


