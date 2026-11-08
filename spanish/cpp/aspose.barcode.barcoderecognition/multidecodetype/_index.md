---
title: "Clase Aspose::BarCode::BarCodeRecognition::MultiDecodeType"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::MultiDecodeType. Tipo de decodificación compuesto en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Tipo de decodificación compuesta.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Agrega un [SingleDecodeType](../singledecodetype/) más al [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Comprueba si esto contiene todos los tipos de códigos de barras. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Contiene alguno de los tipos. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MultiDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Devuelve un valor que indica si esta colección de tipos de decodificación contiene solo el valor especificado de [SingleDecodeType](../singledecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MultiDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../basedecodetype/). |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Excluye [SingleDecodeType](../singledecodetype/) del [MultiDecodeType](./) y devuelve una nueva instancia de [MultiDecodeType](./). |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Devuelve un número de tipos simples. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetSingleTypes](./getsingletypes/)() | Representa una lista de tipos simples. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Inicializa una nueva instancia de la clase [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Método sobrescrito que representa [MultiDecodeType](./) como una cadena. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Convierte la representación en cadena de un [MultiDecodeType](./) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Convierte la representación en cadena de un [SingleDecodeType](../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Convierte la representación de cadena de un [BaseDecodeType](../basedecodetype/) a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Observaciones


Este ejemplo muestra cómo crear tipos compuestos MultiDecode que combinan [SingleDecodeType](../singledecodetype/) y tipos MultiDecode.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## Ver también

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
