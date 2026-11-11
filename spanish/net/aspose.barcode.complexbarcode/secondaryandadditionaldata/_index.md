---
title: "Clase SecondaryAndAdditionalData"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData. Clase para almacenar datos secundarios y adicionales del HIBC LIC"
type: docs
weight: 770
url: /es/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Clase para almacenar los datos secundarios y adicionales HIBC LIC.

```csharp
public class SecondaryAndAdditionalData
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifica la fecha de caducidad. Se utilizará si ExpiryDateFormat no está configurado a None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifica el formato de la fecha de caducidad. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifica el número de lote o lote de producción. El número de lote/lote debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `SecondaryAndAdditionalData`. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Devuelve el código hash de esta instancia. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Instancia datos suplementarios secundarios y adicionales a partir de una cadena según la especificación HIBC LIC. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Convierte los datos a formato de cadena según la especificación HIBC LIC. |

### Ver también

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


