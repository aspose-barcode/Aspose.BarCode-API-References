---
title: "Clase Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext. Clase para codificar y decodificar el texto incrustado en el código Mailmark 2D de Royal Mail en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Class](./get_class/)() const | Identifica la clase del elemento. |
| [get_CustomerContent](./get_customercontent/)() const | Espacio opcional para uso del cliente. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | Tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Contiene el código postal de la dirección de entrega [Address](../address/) con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [get_ItemID](./get_itemid/)() const | Identifica el elemento único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para poder ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Contiene el código postal de devolución al remitente pero sin DPS. El CP (sin DPS) debe cumplir con un formato PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [get_VersionID](./get_versionid/)() const | Identifica la versión del código de barras según cada ID de tipo de información. |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el texto de código a partir de los datos de Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa los datos de Mailmark a partir del texto de código construido. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Constructor. Crea una instancia predeterminada de la clase [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Identifica la clase del elemento. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Espacio opcional para uso del cliente. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | Tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Contiene el código postal de la dirección de entrega [Address](../address/) con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [set_ItemID](./set_itemid/)(int32_t) | Identifica el elemento único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para poder ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Contiene el código postal de devolución al remitente pero sin DPS. El CP (sin DPS) debe cumplir con un formato PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [set_VersionID](./set_versionid/)(System::String) | Identifica la versión del código de barras según cada ID de tipo de información. |
## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
