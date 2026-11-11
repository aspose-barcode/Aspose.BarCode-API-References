---
title: "BarCodeReader.ProcessorSettings"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarCodeReader. Obtiene una configuración para el uso de núcleos del procesador"
type: docs
weight: 140
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Obtiene la configuración del uso de núcleos del procesador.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Ejemplos

Esta muestra muestra cómo usar ProcessorSettings para agregar el máximo rendimiento multihilo.

```csharp
[C#]
//Esto permite usar todos los núcleos para una única llamada a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Esto permite usar el recuento actual de núcleos
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Ver también

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


