---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType class"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType class. Tipo di decodifica singola. Vedi decode type per ottenere l'istanza in C++."
type: docs
weight: 3200
url: /it/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Tipo di decodifica singola. Vedi il tipo di decodifica per ottenere l'istanza.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Restituisce un valore che indica se questa istanza è inclusa nell'elenco specificato. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [SingleDecodeType](./) specificato. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Restituisce un valore che indica se la collezione [MultiDecodeType](../multidecodetype/) specificata contiene solo questo tipo di decodifica. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [SingleDecodeType](./) specificato. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../basedecodetype/) specificato. |
| [get_TypeIndex](./get_typeindex/)() const | Ottiene un indice del tipo di decodifica |
| [get_TypeName](./get_typename/)() const | Ottiene un nome del tipo di decodifica |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetString](./getstring/)() | Converte l'istanza di [SingleDecodeType](./) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Converte l'istanza di [SingleDecodeType](./) nella sua rappresentazione stringa equivalente. Il formato della stringa è: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Converte la rappresentazione stringa del nome di un [SingleDecodeType](./) nella sua istanza. |
| [ToString](./tostring/)() const override | Restituisce il nome del [SingleDecodeType](./) fornito come stringa. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converte la rappresentazione stringa di un [SingleDecodeType](./) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converte la rappresentazione stringa di un [MultiDecodeType](../multidecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converte la rappresentazione stringa di un [BaseDecodeType](../basedecodetype/) nella sua istanza, avendo determinato il tipo concreto. Un valore restituito indica se la conversione è riuscita o meno. |
## Osservazioni


Questo esempio mostra come ottenere l'istanza del tipo di decodifica singola.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Vedi anche

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
