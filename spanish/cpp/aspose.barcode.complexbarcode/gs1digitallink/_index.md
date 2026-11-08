---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. Representa el texto de código GS1 Digital Link para codificar y decodificar como una secuencia ordenada de elementos Application Identifier. Se preserva el orden de origen y los Application Identifier repetidos. El texto de código construido es un URI GS1 Digital Link sin comprimir. Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Representa el texto de código GS1 Digital Link para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preserva el orden de origen y los Identificadores de Aplicación repetidos. El texto de código construido es una URI GS1 Digital Link sin comprimir. Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Agrega un elemento Application Identifier validado. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Crea un GS1 Digital Link copiando todos los elementos del texto de código GS1 y seleccionando la única clave primaria disponible. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Crea un GS1 Digital Link copiando todos los elementos del texto de código GS1 y usando la clave primaria especificada. |
| [get_BarcodeType](./get_barcodetype/)() const | Obtiene el tipo de código de barras utilizado para codificar este GS1 Digital Link. Los tipos compatibles son QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF y Code128. El valor predeterminado es QR. |
| [get_Count](./get_count/)() | Obtiene el número de elementos Application Identifier. |
| [get_Elements](./get_elements/)() | Obtiene una copia de todos los elementos en el orden de origen. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Obtiene el Application Identifier utilizado como clave primaria del Digital Link. Null indica que la clave primaria se selecciona automáticamente cuando se construye el URI. |
| [get_UriStem](./get_uristem/)() const | Obtiene el prefijo de URI absoluto antes del segmento de ruta de la clave primaria GS1. La raíz no contiene una cadena de consulta ni fragmento. |
| [GetAll](./getall/)(System::String) | Obtiene todos los valores de un Identificador de Aplicación en orden de origen. |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras utilizado para codificar este Enlace Digital GS1. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el URI del Enlace Digital GS1 sin comprimir. |
| [GetFirst](./getfirst/)(System::String) | Obtiene el primer valor de un Identificador de Aplicación. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Inicializa un Enlace Digital GS1 vacío con el segmento URI especificado. La clave primaria se selecciona automáticamente cuando hay exactamente un candidato a clave primaria. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Inicializa un Enlace Digital GS1 vacío con el segmento URI especificado y la clave primaria. |
| [idx_get](./idx_get/)(int32_t) | Obtiene un elemento por su posición en la secuencia ordenada. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa esta instancia a partir de un URI de Enlace Digital GS1 sin comprimir. El estado existente se reemplaza solo después de que el URI proporcionado se haya analizado correctamente. El tipo de código de barras seleccionado se conserva. |
| static [Parse](./parse/)(System::String) | Analiza un URI de Enlace Digital GS1 sin comprimir. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Establece el tipo de código de barras utilizado para codificar este Enlace Digital GS1. Los tipos compatibles son QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF y Code128. El valor predeterminado es QR. |
| [ToGS1Codetext](./togs1codetext/)() | Crea un codetexto GS1 independiente que contiene los elementos GS1 actuales. La información solo de URI no se incluye. |
| [ToString](./tostring/)() const override | Devuelve el URI del Enlace Digital GS1 sin comprimir. |
| [ToUriString](./touristring/)() | Formatea el estado actual del objeto como un URI de Enlace Digital GS1 sin comprimir. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Intenta analizar un URI de Enlace Digital GS1 sin comprimir y devuelve errores de validación estructurados. |
| static [Validate](./validate/)(System::String) | Valida un URI de Enlace Digital GS1 sin comprimir sin construir un objeto. |
## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
