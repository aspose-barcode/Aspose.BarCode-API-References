---
title: "método"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Establece la clave pública y privada medida. Si compra una licencia medida, al iniciar la aplicación, esta API debe ser llamada, normalmente, esto es suficiente. Sin embargo, si siempre falla al cargar los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar tal caso, debe comprobar regularmente el estado de la licencia, si está en estado de evaluación, llame a esta API nuevamente en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Establece la clave pública y privada medida. Si usted compra una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, esto es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar ese caso, debe comprobar regularmente el estado de la licencia, y si está en estado de evaluación, llamar a esta API nuevamente.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | System::String | clave pública |
| privateKey | System::String | clave privada |

## Ver también

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
