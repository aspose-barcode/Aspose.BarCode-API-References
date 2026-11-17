---
title: "枚举"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: " enum. 指定 C++ 中不同类型的自动尺寸模式。"
type: docs
weight: 5200
url: /zh/cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


指定自动尺寸模式的不同类型。

```cpp
enum class AutoSizeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 无 | 0 | 已禁用自动调整大小。 |
| 最近 | 1 | 将条码调整为由 ImageWidth 和 ImageHeight 属性指定的最近的最小可能尺寸。保持默认宽高比。 |
| 插值 | 2 | 将条码调整为指定尺寸。尺寸可以通过 ImageWidth 和 ImageHeight 属性指定。缩放后生成的条码可能无效（不可读取）。 |

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
