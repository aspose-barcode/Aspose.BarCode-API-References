---
title: "Classe MultiDecodeType"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Tipo di decodifica composito"
type: docs
weight: 320
url: /it/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Tipo di decodifica composito.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Inizializza una nuova istanza della classe `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Inizializza una nuova istanza della classe `MultiDecodeType`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Restituisce un numero di tipi singoli. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Aggiunge un altro [`SingleDecodeType`](../singledecodetype/) al MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Verifica se contiene tutti i tipi dei codici a barre. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Contiene uno qualsiasi dei tipi. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Restituisce un valore che indica se questa collezione di tipi di decodifica contiene solo il valore specificato di [`SingleDecodeType`](../singledecodetype/). |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Esclude [`SingleDecodeType`](../singledecodetype/) dal MultiDecodeType e restituisce una nuova istanza di MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Restituisce il codice hash per questa istanza. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Rappresenta un elenco di tipi singoli. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Metodo sovrascritto che rappresenta MultiDecodeType come stringa. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita. |

## Esempi

Questo esempio mostra come creare tipi MultiDecode composti che combinano SingleDecodeType e tipi MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Vedi anche

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


