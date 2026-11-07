---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType class"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType class. Classe base per MultiDecodeType e SingleDecodeType in C++."
type: docs
weight: 900
url: /it/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Classe base per [MultiDecodeType](../multidecodetype/) e [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Determina se uno qualsiasi dei tipi di decodifica forniti è incluso in |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Restituisce un valore che indica se questa istanza è uguale a un valore [SingleDecodeType](../singledecodetype/) specificato. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Restituisce un valore che indica se questa istanza è uguale a un valore [MultiDecodeType](../multidecodetype/) specificato. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [BaseDecodeType](./). |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converte la rappresentazione stringa di un [SingleDecodeType](../singledecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converte la rappresentazione stringa di un [MultiDecodeType](../multidecodetype/) nella sua istanza. Un valore restituito indica se la conversione è riuscita o meno. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converte la rappresentazione stringa di un [BaseDecodeType](./) nella sua istanza, dopo aver determinato il tipo concreto. Un valore restituito indica se la conversione è riuscita o meno. |
## Osservazioni


Questo esempio mostra come utilizzare [BaseDecodeType](./) con [SingleDecodeType](../singledecodetype/) e [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
