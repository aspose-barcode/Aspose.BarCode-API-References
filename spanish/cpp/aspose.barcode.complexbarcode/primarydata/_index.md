---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData clase"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData clase. Clase para almacenar datos primarios HIBC LIC en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Clase para almacenar los datos primarios de HIBC LIC.

```cpp
class PrimaryData : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor [PrimaryData](./) especificado. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | Identifica el número de producto o catálogo. El número de producto o catálogo debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ParseFromString](./parsefromstring/)(System::String) | Instancia datos primarios a partir del formato de cadena según la especificación HIBC LIC. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Identifica la fecha del código de identificación del etiquetador. El código de identificación del etiquetador debe ser una cadena alfanumérica de 4 símbolos, con el primer carácter siempre alfabético. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Identifica el número de producto o catálogo. El número de producto o catálogo debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Identifica el ID de unidad de medida. El ID de unidad de medida debe ser un valor entero de 0 a 9. |
| [ToString](./tostring/)() const override | Convierte datos al formato de cadena según la especificación HIBC LIC. |
## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
