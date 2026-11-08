---
title: "Clase Aspose::BarCode::Generation::SymbologyEncodeType"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::Generation::SymbologyEncodeType. Tipo de codificación de simbología. Consulte EncodeTypes para obtener una instancia en C++."
type: docs
weight: 4900
url: /es/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Tipo de codificación de simbología. Consulte [EncodeTypes](../encodetypes/) para obtener una instancia.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseEncodeType](../baseencodetype/). |
| [get_Classification](../baseencodetype/get_classification/)() const | Obtiene una clasificación de esta simbología. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Obtiene un índice del tipo de codificación |
| [get_TypeName](../baseencodetype/get_typename/)() const | Obtiene un nombre del tipo de codificación |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetString](../baseencodetype/getstring/)() | Convierte la instancia de [BaseEncodeType](../baseencodetype/) a su representación de cadena equivalente. El formato de cadena es: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Convierte la instancia de [BaseEncodeType](../baseencodetype/) a su representación de cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Convierte la representación de cadena del nombre de un [BaseEncodeType](../baseencodetype/) a su instancia. |
| [ToString](../baseencodetype/tostring/)() const override | Devuelve el nombre del [BaseEncodeType](../baseencodetype/) proporcionado como una cadena. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Convierte la representación de cadena de un [BaseEncodeType](../baseencodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Convierte la representación de cadena de un [BaseEncodeType](../baseencodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Observaciones


Esta muestra muestra cómo obtener una instancia de la clase [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Ver también

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
