---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Clase para almacenar datos secundarios y adicionales de HIBC LIC en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Clase para almacenar los datos secundarios y adicionales de HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SecondaryAndAdditionalData](./). |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está establecido en None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identifica el formato de la fecha de caducidad. |
| [get_LotNumber](./get_lotnumber/)() const | Identifica el número de lote o lote. El número de lote debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [get_Quantity](./get_quantity/)() const | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ParseFromString](./parsefromstring/)(System::String) | Instancia datos suplementarios secundarios y adicionales a partir de formato de cadena según la especificación HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está establecido en None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identifica el formato de la fecha de caducidad. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identifica el número de lote o lote. El número de lote debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [set_Quantity](./set_quantity/)(int32_t) | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [ToString](./tostring/)() const override | Convierte datos al formato de cadena según la especificación HIBC LIC. |
## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
