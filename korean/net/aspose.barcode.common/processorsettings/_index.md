---
title: "클래스 ProcessorSettings"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Common.ProcessorSettings 클래스. ProcessorSettings는 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다."
type: docs
weight: 470
url: /ko/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings는 멀티스레드 성능 향상을 통해 바코드를 인식하도록 허용합니다.

```csharp
public class ProcessorSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | 코드를 병렬로 실행하기 위한 추가 스레드의 최대 수를 지정합니다 |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | 전체 코어를 사용하려면 필요합니다. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | 사용할 코어 수를 지정합니다. 속성 "UseAllCores"를 "false"로 변경해야 합니다. |

## 예제

이 샘플은 ProcessorSettings를 사용하여 최대 다중 스레드 성능을 추가하는 방법을 보여줍니다

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//이는 단일 BarCodeReader 호출에 모든 코어를 사용할 수 있게 합니다
BarCodeReader.ProcessorSettings.UseAllCores = true;
//이는 현재 코어 수를 사용할 수 있게 합니다
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

### 또 보기

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


