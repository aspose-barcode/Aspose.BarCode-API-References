---
title: "Aspose::BarCode::Common::ProcessorSettings クラス"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Common::ProcessorSettings クラス。ProcessorSettings は、C++ でマルチスレッド化によりパフォーマンスを向上させてバーコードを認識できるようにします。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | コードを並列で実行するための最大追加スレッド数を指定します |
| [get_UseAllCores](./get_useallcores/)() const | すべてのコアを使用するために必要です。 |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | 使用するコア数を指定します。プロパティ "UseAllCores" を "false" に変更する必要があります。 |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | コードを並列で実行するための最大追加スレッド数を指定します |
| [set_UseAllCores](./set_useallcores/)(bool) | すべてのコアを使用するために必要です。 |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | 使用するコア数を指定します。プロパティ "UseAllCores" を "false" に変更する必要があります。 |
## 備考


このサンプルは、[ProcessorSettings](./) を使用して最大のマルチスレッド パフォーマンスを追加する方法を示します
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//これにより、単一の BarCodeReader 呼び出しで全コアを使用できます
BarCodeReader.ProcessorSettings.UseAllCores = true;
//これにより、現在のコア数を使用できます
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

## 関連項目

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
