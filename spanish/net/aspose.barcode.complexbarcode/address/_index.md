---
title: "Clase Address"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.Address. Dirección del acreedor o deudor"
type: docs
weight: 480
url: /es/net/aspose.barcode.complexbarcode/address/
---
## Address class

Dirección del acreedor o deudor.

Puede establecer la calle, el número de casa, el código postal y la ciudad (tipo dirección estructurada) o la línea de dirección 1 y 2 (tipo elementos de dirección combinados). El tipo se establece automáticamente una vez que se define cualquiera de estos campos. Antes de establecer los campos, el tipo de dirección es indeterminado. Si se establecen campos de ambos tipos, el tipo de dirección se vuelve conflictivo. El nombre y el código de país deben estar siempre establecidos a menos que todos los campos estén vacíos.

```csharp
public sealed class Address : IEquatable<Address>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Address](address/)() | Crea una instancia de Address |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Obtiene o establece la línea de dirección 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Obtiene o establece la línea de dirección 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Obtiene o establece el código de país ISO de dos letras. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Obtiene o establece el número de casa. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Obtiene o establece el nombre, ya sea el nombre y apellido de una persona física o el nombre de la empresa de una persona jurídica. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Obtiene o establece el código postal. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Obtiene o establece la calle. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Obtiene o establece la ciudad o pueblo. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Obtiene el tipo de dirección. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Borra todos los campos y establece el tipo como Indeterminado. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Determina si la dirección especificada es igual a la dirección actual. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Determina si el objeto especificado es igual al objeto actual. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Obtiene el código hash de esta instancia. |

### Ver también

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


