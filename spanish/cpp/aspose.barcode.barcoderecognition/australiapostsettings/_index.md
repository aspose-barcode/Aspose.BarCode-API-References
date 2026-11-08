---
title: "Clase Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings. Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost.

```cpp
class AustraliaPostSettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Interfaz pública para la decodificación del Campo de Información del Cliente que se usa en la simbología AustraliaPost. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Obtiene el Tipo de Interpretación para la Información del Cliente de AustralianPost [BarCode.Default](../checksumvalidation/) es [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Interfaz pública para la decodificación del Campo de Información del Cliente que se usa en la simbología AustraliaPost. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Establece el Tipo de Interpretación para la Información del Cliente de AustralianPost [BarCode.Default](../checksumvalidation/) es [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el Campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z". |
## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
