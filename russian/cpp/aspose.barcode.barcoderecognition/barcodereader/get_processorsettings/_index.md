---
title: "method"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: "метод. Получает настройки использования ядер процессора в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Получает настройки использования ядер процессора.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Примечания


Этот пример показывает, как использовать ProcessorSettings для достижения максимальной многопоточной производительности
```cpp
[C#]
//это позволяет использовать все ядра для одного вызова BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//это позволяет использовать текущее количество ядер
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## См. также

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
