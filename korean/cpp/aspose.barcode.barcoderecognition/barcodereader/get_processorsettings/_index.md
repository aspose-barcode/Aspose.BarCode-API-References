---
title: "메서드"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 프로세서 코어 사용 설정을 가져옵니다."
type: docs
weight: 100
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


프로세서 코어 사용에 대한 설정을 가져옵니다.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## 비고


이 샘플은 ProcessorSettings를 사용하여 최대 다중 스레드 성능을 추가하는 방법을 보여줍니다.
```cpp
[C#]
//이렇게 하면 단일 BarCodeReader 호출에 전체 코어를 사용할 수 있습니다
BarCodeReader.ProcessorSettings.UseAllCores = true;
//이렇게 하면 현재 코어 수를 사용할 수 있습니다
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## 또 보기

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
