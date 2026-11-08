---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::DataMatrixParameters class. Parámetros DataMatrix en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Parámetros de DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [get_EccType](./get_ecctype/)() const | Obtiene un tipo ECC de Datamatrix. Valor predeterminado: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Obtiene la codificación ECI. Se usa cuando EncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Modo de codificación del código de barras Datamatrix. Valor predeterminado: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. Valor predeterminado: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Los valores de los caracteres macro 05 y 06 se usan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con [DataMatrixEccType.Ecc200](../datamatrixecctype/) o [DataMatrixEccType.EccAuto](../datamatrixecctype/). No se pueden usar con [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Valor predeterminado: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | ID de código de barras para el modo de Anexado Estructurado del código Datamatrix. Valor predeterminado: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Recuento de códigos de barras para el modo de Anexado Estructurado del código Datamatrix. Valor predeterminado: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Identificador de archivo para el modo Structured Append del código de barras Datamatrix. Valor predeterminado: 0 |
| [get_Version](./get_version/)() const | Obtiene el tamaño del símbolo Datamatrix. Valor predeterminado: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Relación altura/ancho del módulo 2D [BarCode](../../aspose.barcode/). |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Establece un tipo ECC de Datamatrix. Valor predeterminado: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Establece la codificación ECI. Se usa cuando EncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Modo de codificación del código de barras Datamatrix. Valor predeterminado: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. Valor predeterminado: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Los valores de los caracteres macro 05 y 06 se usan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con [DataMatrixEccType.Ecc200](../datamatrixecctype/) o [DataMatrixEccType.EccAuto](../datamatrixecctype/). No se pueden usar con [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Valor predeterminado: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | ID de código de barras para el modo de Anexado Estructurado del código Datamatrix. Valor predeterminado: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Recuento de códigos de barras para el modo de Anexado Estructurado del código Datamatrix. Valor predeterminado: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Identificador de archivo para el modo Structured Append del código de barras Datamatrix. Valor predeterminado: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Establece el tamaño del símbolo Datamatrix. Valor predeterminado: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [DataMatrixParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
