---
title: "método"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene una configuración del uso de núcleos del procesador en C++."
type: docs
weight: 100
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Obtiene una configuración de uso de núcleos del procesador.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Observaciones


Este ejemplo muestra cómo usar ProcessorSettings para añadir el máximo rendimiento multihilo
```cpp
[C#]
//esto permite usar todos los núcleos para una única llamada a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//esto permite usar la cantidad actual de núcleos
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Ver también

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
