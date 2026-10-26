---
title: Aspose::BarCode::BarCodeRecognition::Iso15416Quality class
linktitle: Iso15416Quality
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::Iso15416Quality class. Stores barcode quality grades calculated according to the ISO/IEC 15416 standard for 1D barcodes in C++.'
type: docs
weight: 2200
url: /cpp/aspose.barcode.barcoderecognition/iso15416quality/
---
## Iso15416Quality class


Stores barcode quality grades calculated according to the ISO/IEC 15416 standard for 1D barcodes.

```cpp
class Iso15416Quality : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Decodability](./get_decodability/)() const | Gets the decodability grade based on the accuracy of bar and space widths. |
| [get_Decode](./get_decode/)() const | Gets the decode grade indicating whether the barcode can be decoded using the reference decode algorithm. |
| [get_Defects](./get_defects/)() const | Gets the defects grade based on reflectance irregularities within bars and spaces. |
| [get_DetailedGrades](./get_detailedgrades/)() const | Gets additional quality grades, including symbology-specific checks. |
| [get_Grade](./get_grade/)() const | Gets the overall barcode quality grade according to ISO/IEC 15416. |
| [get_MinimumEdgeContrast](./get_minimumedgecontrast/)() const | Gets the minimum edge contrast grade based on the smallest reflectance difference between adjacent bars and spaces. |
| [get_MinimumReflectance](./get_minimumreflectance/)() const | Gets the minimum reflectance grade based on the darkest bar reflectance. |
| [get_Modulation](./get_modulation/)() const | Gets the modulation grade based on the uniformity of edge contrast throughout the barcode. |
| [get_SymbolContrast](./get_symbolcontrast/)() const | Gets the symbol contrast grade based on the difference between maximum and minimum reflectance. |
## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
