---
title: "Metered.SetMeteredKey"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método de Metered. Establece la clave pública y privada de Metered. Si compras una licencia Metered al iniciar la aplicación, esta API debe llamarse normalmente; con eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se cambiará a estado de evaluación; para evitar este caso, deberías comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente"
type: docs
weight: 30
url: /es/net/aspose.barcode/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Establece la clave pública y privada medida. Si compra una licencia medida, al iniciar la aplicación, esta API debe ser llamada; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | Cadena | clave pública |
| privateKey | Cadena | clave privada |

### Ver también

* class [Metered](../)
* namespace [Aspose.BarCode](../../../aspose.barcode/)
* assembly [Aspose.BarCode](../../../)


