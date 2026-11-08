---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Modo de codificación de código de barras Pdf417 en C++."
type: docs
weight: 7900
url: /es/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Modo de codificación del código de barras Pdf417

```cpp
enum class Pdf417EncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | En modo Auto, el CodeText se codifica con la máxima compacidad de datos. Los caracteres Unicode se vuelven a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. |
| Binario | 1 | En modo Binario, el CodeText se codifica con la máxima compacidad de datos. Si se encuentra un carácter Unicode, se lanza una excepción. |
| ECI | 2 | En modo ECI, todo el mensaje se vuelve a codificar en la codificación especificada por ECIEncoding con la inserción de un identificador ECI. Si se encuentra un carácter que no es compatible con la codificación ECI seleccionada, se lanza una excepción. Tenga en cuenta que algunos escáneres antiguos (previos a 2006) pueden no ser compatibles con este modo. |
| Extendido | 3 |  |

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
