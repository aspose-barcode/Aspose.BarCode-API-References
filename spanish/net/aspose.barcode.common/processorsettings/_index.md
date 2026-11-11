---
title: "Clase ProcessorSettings"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Common.ProcessorSettings. ProcessorSettings permite reconocer códigos de barras con aumento de rendimiento mediante multihilo."
type: docs
weight: 470
url: /es/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings permite reconocer códigos de barras con un aumento de rendimiento mediante multihilos.

```csharp
public class ProcessorSettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Especifique el número máximo de hilos adicionales para ejecutar el código en paralelo |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Es necesario para usar todos los núcleos. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Especifique el número de núcleos a usar. Necesita cambiar la propiedad "UseAllCores" a "false". |

## Ejemplos

Esta muestra muestra cómo usar ProcessorSettings para agregar el máximo rendimiento multihilo.

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//Esto permite usar todos los núcleos para una única llamada a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Esto permite usar el recuento actual de núcleos
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

### Ver también

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


