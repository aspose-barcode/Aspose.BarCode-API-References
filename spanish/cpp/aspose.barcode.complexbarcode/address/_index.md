---
title: "Clase Aspose::BarCode::ComplexBarcode::Address"
linktitle: "Dirección"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::ComplexBarcode::Address. Dirección del acreedor o deudor en C++."
type: docs
weight: 100
url: /es/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Address](./address/)() | Crea una instancia de [Address](./) |
| [Clear](./clear/)() | Borra todos los campos y establece el tipo a [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si el objeto especificado es igual al objeto actual. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Determina si la dirección especificada es igual a la dirección actual. |
| [get_AddressLine1](./get_addressline1/)() const | Obtiene la línea 1 de la dirección. |
| [get_AddressLine2](./get_addressline2/)() const | Obtiene la línea 2 de la dirección. |
| [get_CountryCode](./get_countrycode/)() const | Obtiene el código de país ISO de dos letras. |
| [get_HouseNo](./get_houseno/)() const | Obtiene el número de casa. |
| [get_Name](./get_name/)() const | Obtiene el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica. |
| [get_PostalCode](./get_postalcode/)() const | Obtiene el código postal. |
| [get_Street](./get_street/)() const | Obtiene la calle. |
| [get_Town](./get_town/)() const | Obtiene la localidad o ciudad. |
| [get_Type](./get_type/)() const | Obtiene el tipo de dirección. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash de esta instancia. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Establece la línea 1 de la dirección. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Establece la línea 2 de la dirección. |
| [set_CountryCode](./set_countrycode/)(System::String) | Establece el código de país ISO de dos letras. |
| [set_HouseNo](./set_houseno/)(System::String) | Establece el número de casa. |
| [set_Name](./set_name/)(System::String) | Establece el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica. |
| [set_PostalCode](./set_postalcode/)(System::String) | Establece el código postal. |
| [set_Street](./set_street/)(System::String) | Establece la calle. |
| [set_Town](./set_town/)(System::String) | Establece la localidad o la ciudad. |
## Observaciones


Puede establecer la calle, el número de casa, el código postal y la localidad (tipo *dirección estructurada*) o la línea de dirección 1 y 2 (tipo *elementos de dirección combinados*). El tipo se establece automáticamente una vez que se completa cualquiera de estos campos. Antes de establecer los campos, el tipo de dirección es *indeterminado*. Si se establecen campos de ambos tipos, el tipo de dirección pasa a ser *conflictivo*. El nombre y el código de país deben establecerse siempre, a menos que todos los campos estén vacíos.
## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
