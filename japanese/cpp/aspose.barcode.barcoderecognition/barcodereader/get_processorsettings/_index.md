---
title: "メソッド"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++ でプロセッサコアの使用設定を取得します。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


プロセッサコアの使用設定を取得します。

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## 備考


このサンプルは、ProcessorSettings を使用して最大のマルチスレッドパフォーマンスを追加する方法を示しています。
```cpp
[C#]
//これにより、単一の BarCodeReader 呼び出しで全コアを使用できます
BarCodeReader.ProcessorSettings.UseAllCores = true;
//これにより、現在のコア数を使用できます
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## 関連項目

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
