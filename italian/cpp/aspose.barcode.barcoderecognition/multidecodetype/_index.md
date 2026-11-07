---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType classe"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType classe. Tipo di decodifica composito in C++."
type: docs
weight: 2600
url: /it/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Tipo di decodifica composita.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Aggiunge un altro [SingleDecodeType](../singledecodetype/) al [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Verifica se contiene tutti i tipi dei codici a barre. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Contiene uno dei tipi. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [MultiDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Restituisce un valore che indica se questa collezione di tipi di decodifica contiene solo il valore specificato di [SingleDecodeType](../singledecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [MultiDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [BaseDecodeType](../basedecodetype/) specificato. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Esclude [SingleDecodeType](../singledecodetype/) dal [MultiDecodeType](./) e restituisce una nuova istanza di [MultiDecodeType](./). |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Restituisce un numero di tipi singoli. |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetSingleTypes](./getsingletypes/)() | Rappresenta un elenco di tipi singoli. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Inizializza una nuova istanza della classe [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inizializza una nuova istanza della classe [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Metodo sovrascritto che rappresenta [MultiDecodeType](./) come stringa. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converte la rappresentazione stringa di un [MultiDecodeType](./) nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o meno. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converte la rappresentazione stringa di un [SingleDecodeType](../singledecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converte la rappresentazione stringa di un [BaseDecodeType](../basedecodetype/) nella sua istanza, avendo determinato il tipo concreto. Un valore restituito indica se la conversione è riuscita o meno. |
## Osservazioni


Questo esempio mostra come creare tipi MultiDecode composti che combinano [SingleDecodeType](../singledecodetype/) e tipi MultiDecode.
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

## Vedi anche

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
