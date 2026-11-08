---
title: "Clase Aspose::BarCode::Generation::AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::AztecParameters. Parámetros Aztec en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Parámetros Aztec.

```cpp
class AztecParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Obtiene la codificación ECI. Usado cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Obtiene un modo de codificación Aztec. Valor predeterminado: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [get_LayersCount](./get_layerscount/)() const | Obtiene el recuento de capas del símbolo Aztec. El recuento de capas debe estar en el rango de 1 a 3 para el modo Compacto y en el rango de 1 a 32 para el modo de Rango Completo. Valor predeterminado: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID del código de barras para el modo Structured Append del código de barras Aztec. El ID del código de barras debe estar en el rango de 1 al número de códigos de barras. Valor predeterminado: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El ID de archivo no debe contener espacios. Valor predeterminado: cadena vacía |
| [get_SymbolMode](./get_symbolmode/)() const | Obtiene un modo de símbolo Aztec. Valor predeterminado: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Establece un modo de codificación Aztec. Valor predeterminado: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Establece el recuento de capas del símbolo Aztec. El recuento de capas debe estar en el rango de 1 a 3 para el modo Compacto y en el rango de 1 a 32 para el modo de Rango Completo. Valor predeterminado: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID del código de barras para el modo Structured Append del código de barras Aztec. El ID del código de barras debe estar en el rango de 1 al número de códigos de barras. Valor predeterminado: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | ID de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El ID de archivo no debe contener espacios. Valor predeterminado: cadena vacía |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Establece un modo de símbolo Aztec. Valor predeterminado: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [AztecParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
