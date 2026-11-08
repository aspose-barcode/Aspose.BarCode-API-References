---
title: "Clase Aspose::BarCode::Common::ProcessorSettings"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Common::ProcessorSettings. ProcessorSettings permite reconocer códigos de barras con aumento de rendimiento mediante multihilo en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Especifique el número máximo de hilos adicionales para ejecutar el código en paralelo |
| [get_UseAllCores](./get_useallcores/)() const | Es necesario para usar todos los núcleos. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Especifique el número de núcleos a usar. Necesita cambiar la propiedad "UseAllCores" a "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Especifique el número máximo de hilos adicionales para ejecutar el código en paralelo |
| [set_UseAllCores](./set_useallcores/)(bool) | Es necesario para usar todos los núcleos. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Especifique el número de núcleos a usar. Necesita cambiar la propiedad "UseAllCores" a "false". |
## Observaciones


Este ejemplo muestra cómo usar [ProcessorSettings](./) para añadir el máximo rendimiento multihilo
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//esto permite usar todos los núcleos para una única llamada a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//esto permite usar la cantidad actual de núcleos
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

## Ver también

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
