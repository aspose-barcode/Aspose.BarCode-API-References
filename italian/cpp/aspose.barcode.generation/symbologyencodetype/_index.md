---
title: "Aspose::BarCode::Generation::SymbologyEncodeType classe"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::SymbologyEncodeType classe. Tipo di codifica della simbologia. Vedere EncodeTypes per ottenere un'istanza in C++."
type: docs
weight: 4900
url: /it/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Tipo di codifica della simbologia. Vedere [EncodeTypes](../encodetypes/) per ottenere un'istanza.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [BaseEncodeType](../baseencodetype/). |
| [get_Classification](../baseencodetype/get_classification/)() const | Ottiene una classificazione di questa simbologia. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Ottiene un indice del tipo di codifica |
| [get_TypeName](../baseencodetype/get_typename/)() const | Ottiene un nome del tipo di codifica |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetString](../baseencodetype/getstring/)() | Converte l'istanza di [BaseEncodeType](../baseencodetype/) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Converte l'istanza di [BaseEncodeType](../baseencodetype/) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Converte la rappresentazione stringa del nome di un [BaseEncodeType](../baseencodetype/) nella sua istanza. |
| [ToString](../baseencodetype/tostring/)() const override | Restituisce il nome del [BaseEncodeType](../baseencodetype/) fornito come stringa. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converte la rappresentazione stringa di un [BaseEncodeType](../baseencodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Converte la rappresentazione stringa di un [BaseEncodeType](../baseencodetype/) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita. |
## Osservazioni


Questo esempio mostra come ottenere un'istanza della classe [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Vedi anche

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
