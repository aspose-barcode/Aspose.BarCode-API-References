---
title: "Clase Metered"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Metered. Proporciona métodos para establecer la clave medida"
type: docs
weight: 1770
url: /es/net/aspose.barcode/metered/
---
## Metered class

Proporciona métodos para establecer la clave de medición.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Obtiene el nombre del producto licenciado |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada medida. Si compra una licencia medida, al iniciar la aplicación, esta API debe ser llamada; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Obtiene el crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Verifique si el medido está licenciado |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada del medido

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


