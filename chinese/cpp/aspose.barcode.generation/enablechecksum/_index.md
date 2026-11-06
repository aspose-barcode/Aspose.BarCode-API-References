---
title: "枚举"
linktitle: "启用校验和"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 6700
url: /zh/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 默认 | 0 | 如果规范要求校验和 - 将会附加。 |
| 是 | 1 | 如果可能，始终使用校验和。 |
| 否 | 2 | 不要使用校验和。 |

## 备注


在生成 1D 条码时启用校验和。

默认情况下，对于必须包含校验和的符号视为 Yes，对于仅可能包含校验和的符号视为 No。

从不使用校验和：Codabar

可以使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

始终使用校验和：其余符号
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
