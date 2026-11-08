---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::DotCodeParameters class. Parámetros DotCode en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Parámetros de DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [get_Columns](./get_columns/)() const | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5. Valor predeterminado: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode está en Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [get_Rows](./get_rows/)() const | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5. Valor predeterminado: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identifica el ID del código de barras en modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identifica el recuento de códigos de barras en modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor entre 1 y 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [set_Columns](./set_columns/)(int32_t) | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5. Valor predeterminado: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode está en Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Indica si el código se utiliza para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [set_Rows](./set_rows/)(int32_t) | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5. Valor predeterminado: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identifica el ID del código de barras en modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identifica el recuento de códigos de barras en modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor entre 1 y 35. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [DotCodeParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
