---
title: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality class"
linktitle: "Iso15416Quality"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality class. Сохраняет оценки качества штрихкода, рассчитанные в соответствии со стандартом ISO/IEC 15416 для 1D штрихкодов на C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.barcode.barcoderecognition/iso15416quality/
---
## Iso15416Quality class


Сохраняет оценки качества штрихкода, рассчитанные в соответствии со стандартом ISO/IEC 15416 для 1D штрихкодов.

```cpp
class Iso15416Quality : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Decodability](./get_decodability/)() const | Получает оценку декодируемости на основе точности ширины штрихов и пробелов. |
| [get_Decode](./get_decode/)() const | Получает оценку декодирования, указывающую, может ли штрихкод быть декодирован с использованием эталонного алгоритма декодирования. |
| [get_Defects](./get_defects/)() const | Получает оценку дефектов на основе нерегулярностей отражения внутри штрихов и пробелов. |
| [get_DetailedGrades](./get_detailedgrades/)() const | Получает дополнительные оценки качества, включая проверки, специфичные для символьных систем. |
| [get_Grade](./get_grade/)() const | Получает общую оценку качества штрихкода в соответствии с ISO/IEC 15416. |
| [get_MinimumEdgeContrast](./get_minimumedgecontrast/)() const | Получает минимальную оценку контраста краёв на основе наименьшей разницы отражения между соседними штрихами и пробелами. |
| [get_MinimumReflectance](./get_minimumreflectance/)() const | Получает минимальную оценку отражения на основе отражения самого тёмного штриха. |
| [get_Modulation](./get_modulation/)() const | Получает оценку модуляции на основе однородности контраста краёв по всему штрихкоду. |
| [get_SymbolContrast](./get_symbolcontrast/)() const | Получает степень контраста символа на основе разницы между максимальной и минимальной отражательной способностью. |
## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
