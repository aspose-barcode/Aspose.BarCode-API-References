---
title: "Aspose::BarCode::Generation::BaseEncodeType class"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::BaseEncodeType class. Clase base para SymbologyEncodeType en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Clase base para [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseEncodeType](./). |
| [get_Classification](./get_classification/)() const | Obtiene una clasificación de esta simbología. |
| [get_TypeIndex](./get_typeindex/)() const | Obtiene un índice del tipo de codificación |
| [get_TypeName](./get_typename/)() const | Obtiene un nombre del tipo de codificación |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [GetString](./getstring/)() | Convierte la instancia de [BaseEncodeType](./) a su representación de cadena equivalente. El formato de cadena es: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Convierte la instancia de [BaseEncodeType](./) a su representación de cadena equivalente. El formato de cadena es: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Convierte la representación en cadena del nombre de un [BaseEncodeType](./) a su instancia. |
| [ToString](./tostring/)() const override | Devuelve el nombre del [BaseEncodeType](./) dado como una cadena. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Convierte la representación en cadena de un [BaseEncodeType](./) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Convierte la representación en cadena de un [BaseEncodeType](./) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
