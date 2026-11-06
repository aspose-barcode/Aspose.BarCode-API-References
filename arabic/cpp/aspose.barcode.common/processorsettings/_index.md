---
title: "فئة Aspose::BarCode::Common::ProcessorSettings"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Common::ProcessorSettings. تسمح ProcessorSettings بالتعرف على الباركودات باستخدام تعدد الخيوط لزيادة الأداء في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي |
| [get_UseAllCores](./get_useallcores/)() const | مطلوب لاستخدام جميع الأنوية. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | حدد عدد الأنوية التي تريد استخدامها. تحتاج إلى تغيير الخاصية "UseAllCores" إلى "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | حدد الحد الأقصى لعدد الخيوط الإضافية لتشغيل الشيفرة بالتوازي |
| [set_UseAllCores](./set_useallcores/)(bool) | مطلوب لاستخدام جميع الأنوية. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | حدد عدد الأنوية التي تريد استخدامها. تحتاج إلى تغيير الخاصية "UseAllCores" إلى "false". |
## ملاحظات


يعرض هذا المثال كيفية استخدام [ProcessorSettings](./) لإضافة أقصى أداء متعدد الخيوط
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//هذا يسمح باستخدام جميع الأنوية لاستدعاء واحد لـ BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//هذا يسمح باستخدام عدد الأنوية الحالي
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

## انظر أيضًا

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
