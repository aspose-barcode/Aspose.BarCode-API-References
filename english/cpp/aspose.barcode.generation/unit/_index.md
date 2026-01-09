---
title: Aspose::BarCode::Generation::Unit class
linktitle: Unit
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::Unit class. Specifies the size value in different units (Pixel, Inches, etc.) in C++.'
type: docs
weight: 4500
url: /cpp/aspose.barcode.generation/unit/
---
## Unit class


Specifies the size value in different units (Pixel, Inches, etc.).

```cpp
class Unit : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines whether this instance and a specified object, which must also be a [Unit](./) object, have the same value. |
| [get_Document](./get_document/)() | Gets size value in document units. |
| [get_Inches](./get_inches/)() | Gets size value in inches. |
| [get_Millimeters](./get_millimeters/)() | Gets size value in millimeters. |
| [get_Pixels](./get_pixels/)() | Gets size value in pixels. |
| [get_Point](./get_point/)() | Gets size value in point. |
| [get_Resolution](./get_resolution/)() | Resolution |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this object. |
| [set_Document](./set_document/)(float) | Sets size value in document units. |
| [set_Inches](./set_inches/)(float) | Sets size value in inches. |
| [set_Millimeters](./set_millimeters/)(float) | Sets size value in millimeters. |
| [set_Pixels](./set_pixels/)(float) | Sets size value in pixels. |
| [set_Point](./set_point/)(float) | Sets size value in point. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [Unit](./). |
## Remarks


This sample shows how to create and save a [BarCode](../../aspose.barcode/) image. 
```cpp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
