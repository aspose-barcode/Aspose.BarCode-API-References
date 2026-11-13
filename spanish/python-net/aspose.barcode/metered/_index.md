---
title: "Metered"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode/metered/
---

## Metered class

Proporciona métodos para establecer la clave medida.

El tipo Metered expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Metered() | Inicializa una nueva instancia de la clase Metered |
## Métodos
| Nombre | Descripción |
| :- | :- |
| set_metered_key(public_key, private_key) | Establece la clave pública y privada con medición.<br/>            Si compra una licencia con medición, al iniciar la aplicación, debe llamarse a esta API; normalmente, esto es suficiente. <br/>            Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación, <br/>            para evitar este caso, debe comprobar regularmente el estado de la licencia; si está en estado de evaluación, llame a esta API nuevamente. |
| get_consumption_quantity() | Obtiene el tamaño del archivo de consumo |
| get_consumption_credit() | Obtiene el crédito de consumo |
| get_product_name() | Obtiene el nombre del producto licenciado |
| is_metered_licensed() | Comprueba si la licencia con medición está activada |

### Ver también

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

