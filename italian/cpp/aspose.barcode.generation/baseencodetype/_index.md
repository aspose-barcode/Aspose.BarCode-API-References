---
title: "Aspose::BarCode::Generation::BaseEncodeType classe"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::BaseEncodeType classe. Classe base per SymbologyEncodeType in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Classe base per [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseEncodeType](./) specificato. |
| [get_Classification](./get_classification/)() const | Ottiene una classificazione di questa simbologia. |
| [get_TypeIndex](./get_typeindex/)() const | Ottiene un indice del tipo di codifica |
| [get_TypeName](./get_typename/)() const | Ottiene un nome del tipo di codifica |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetString](./getstring/)() | Converte l'istanza di [BaseEncodeType](./) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Converte l'istanza di [BaseEncodeType](./) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Converte la rappresentazione stringa del nome di un [BaseEncodeType](./) nella sua istanza. |
| [ToString](./tostring/)() const override | Restituisce il nome del [BaseEncodeType](./) fornito come stringa. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converte la rappresentazione stringa di un [BaseEncodeType](./) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Converte la rappresentazione stringa di un [BaseEncodeType](./) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
