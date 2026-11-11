---
title: "Clase MailmarkCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.MailmarkCodetext. Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados."
type: docs
weight: 670
url: /es/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro) "5" - Diferido (Retail) "6" - Aire (Retail) (para uso futuro) "7" - Superficie (Retail) (para uso futuro) "8" - Premium (Network Access) "9" - Estándar (Network Access) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que indica el internacional "XY11 " (nota los 5 espacios finales) o un patrón de caracteres que indica un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Nulo o Prueba "1" – Carta "2" – Carta grande |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | El valor máximo es 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Los valores máximos son 99 para Barcode C y 999999 para Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Actualmente "1" – Para código de barras Mailmark (0 y 2 a 9 y de la A a la Z reservados para uso futuro) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Construye codetext a partir de datos Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Inicializa los datos Mailmark a partir del codetext construido. |

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


