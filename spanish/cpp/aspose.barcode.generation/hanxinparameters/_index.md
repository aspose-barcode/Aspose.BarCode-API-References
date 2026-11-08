---
title: "Clase Aspose::BarCode::Generation::HanXinParameters"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::HanXinParameters. Parámetros Han Xin en C++."
type: docs
weight: 2900
url: /es/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Parámetros de Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual contiene todas las codificaciones de conjuntos de caracteres bien conocidas. |
| [get_EncodeMode](./get_encodemode/)() const | Modo de codificación HanXin. Valor predeterminado: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivel de corrección de errores Reed-Solomon para el código de barras Han Xin. De bajo a alto: L1, L2, L3, L4. ver ErrorLevel. |
| [get_Version](./get_version/)() const | Versión del código HanXin. De Version01 a Version84 para el código Han Xin. El valor predeterminado es [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual contiene todas las codificaciones de conjuntos de caracteres bien conocidas. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | Modo de codificación HanXin. Valor predeterminado: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Nivel de corrección de errores Reed-Solomon para el código de barras Han Xin. De bajo a alto: L1, L2, L3, L4. ver ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Versión del código HanXin. De Version01 a Version84 para el código Han Xin. El valor predeterminado es [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [HanXinParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
