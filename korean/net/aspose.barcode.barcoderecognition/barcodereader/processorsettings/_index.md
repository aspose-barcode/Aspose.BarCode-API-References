---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 속성. 프로세서 코어 사용 설정을 가져옵니다"
type: docs
weight: 140
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

프로세서 코어 사용 설정을 가져옵니다.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## 예제

이 샘플은 ProcessorSettings를 사용하여 최대 다중 스레드 성능을 추가하는 방법을 보여줍니다

```csharp
[C#]
//이는 단일 BarCodeReader 호출에 모든 코어를 사용할 수 있게 합니다
BarCodeReader.ProcessorSettings.UseAllCores = true;
//이는 현재 코어 수를 사용할 수 있게 합니다
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### 또 보기

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


