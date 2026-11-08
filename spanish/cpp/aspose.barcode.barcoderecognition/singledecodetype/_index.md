---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType clase"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType clase. Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia en C++."
type: docs
weight: 3200
url: /es/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Tipo de decodificación único. Consulte el tipo de decodificación para obtener una instancia.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Devuelve un valor que indica si esta instancia está incluida en la lista especificada. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SingleDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Devuelve un valor que indica si la colección especificada de [MultiDecodeType](../multidecodetype/) contiene solo este tipo de decodificación. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SingleDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](../basedecodetype/). |
| [get_TypeIndex](./get_typeindex/)() const | Obtiene un índice del tipo de decodificación |
| [get_TypeName](./get_typename/)() const | Obtiene un nombre del tipo de decodificación |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetString](./getstring/)() | Convierte la instancia de [SingleDecodeType](./) a su representación de cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Convierte la instancia de [SingleDecodeType](./) a su representación de cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Convierte la representación de cadena del nombre de un [SingleDecodeType](./) a su instancia. |
| [ToString](./tostring/)() const override | Devuelve el nombre del [SingleDecodeType](./) dado como una cadena. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Convierte la representación de cadena de un [SingleDecodeType](./) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Convierte la representación de cadena de un [MultiDecodeType](../multidecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Convierte la representación de cadena de un [BaseDecodeType](../basedecodetype/) a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Observaciones


Este ejemplo muestra cómo obtener una instancia del tipo de decodificación único.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Ver también

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
