---
title: "Clase Aspose::BarCode::Generation::Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::Unit. Especifica el valor de tamaño en diferentes unidades (píxel, pulgadas, etc.) en C++."
type: docs
weight: 5000
url: /es/cpp/aspose.barcode.generation/unit/
---
## Unit class


Especifica el valor de tamaño en diferentes unidades (píxel, pulgadas, etc.).

```cpp
class Unit : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si esta instancia y un objeto especificado, que también debe ser un objeto [Unit](./), tienen el mismo valor. |
| [get_Document](./get_document/)() | Obtiene el valor de tamaño en unidades del documento. |
| [get_Inches](./get_inches/)() | Obtiene el valor de tamaño en pulgadas. |
| [get_Millimeters](./get_millimeters/)() | Obtiene el valor de tamaño en milímetros. |
| [get_Pixels](./get_pixels/)() | Obtiene el valor de tamaño en píxeles. |
| [get_Point](./get_point/)() | Obtiene el valor de tamaño en puntos. |
| [get_Resolution](./get_resolution/)() const | Resolución |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de este objeto. |
| [set_Document](./set_document/)(float) | Establece el valor de tamaño en unidades del documento. |
| [set_Inches](./set_inches/)(float) | Establece el valor de tamaño en pulgadas. |
| [set_Millimeters](./set_millimeters/)(float) | Establece el valor de tamaño en milímetros. |
| [set_Pixels](./set_pixels/)(float) | Establece el valor de tamaño en píxeles. |
| [set_Point](./set_point/)(float) | Establece el valor de tamaño en puntos. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [Unit](./). |
## Observaciones


Este ejemplo muestra cómo crear y guardar una imagen de [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
