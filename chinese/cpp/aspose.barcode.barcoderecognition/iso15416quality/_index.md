---
title: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality 类"
linktitle: "Iso15416Quality"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality 类。存储根据 ISO/IEC 15416 标准为一维条码在 C++ 中计算的条码质量等级。"
type: docs
weight: 2200
url: /zh/cpp/aspose.barcode.barcoderecognition/iso15416quality/
---
## Iso15416Quality class


根据 ISO/IEC 15416 标准为 1D 条码计算的条码质量等级存储。

```cpp
class Iso15416Quality : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Decodability](./get_decodability/)() const | 获取基于条和空宽度精度的可解码性等级。 |
| [get_Decode](./get_decode/)() const | 获取解码等级，指示条码是否可以使用参考解码算法进行解码。 |
| [get_Defects](./get_defects/)() const | 获取基于条和空内部反射率不规则性的缺陷等级。 |
| [get_DetailedGrades](./get_detailedgrades/)() const | 获取附加质量等级，包括特定符号检查。 |
| [get_Grade](./get_grade/)() const | 获取根据 ISO/IEC 15416 的整体条码质量等级。 |
| [get_MinimumEdgeContrast](./get_minimumedgecontrast/)() const | 获取基于相邻条和空之间最小反射率差异的最小边缘对比度等级。 |
| [get_MinimumReflectance](./get_minimumreflectance/)() const | 获取基于最暗条的反射率的最小反射率等级。 |
| [get_Modulation](./get_modulation/)() const | 获取基于整个条码边缘对比度均匀性的调制等级。 |
| [get_SymbolContrast](./get_symbolcontrast/)() const | 获取基于最大和最小反射率差异的符号对比度等级。 |
## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
