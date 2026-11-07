---
title: "Aspose::BarCode::Common::ProcessorSettings 클래스"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Common::ProcessorSettings 클래스. ProcessorSettings는 C++에서 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | 코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다. |
| [get_UseAllCores](./get_useallcores/)() const | 전체 코어를 사용하려면 필요합니다. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | 사용할 코어 수를 지정합니다. 속성 "UseAllCores"를 "false"로 변경해야 합니다. |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | 코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다. |
| [set_UseAllCores](./set_useallcores/)(bool) | 전체 코어를 사용하려면 필요합니다. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | 사용할 코어 수를 지정합니다. 속성 "UseAllCores"를 "false"로 변경해야 합니다. |
## 비고


이 샘플은 [ProcessorSettings](./)를 사용하여 최대 멀티스레드 성능을 추가하는 방법을 보여줍니다
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//이렇게 하면 단일 BarCodeReader 호출에 전체 코어를 사용할 수 있습니다
BarCodeReader.ProcessorSettings.UseAllCores = true;
//이렇게 하면 현재 코어 수를 사용할 수 있습니다
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

## 또 보기

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
