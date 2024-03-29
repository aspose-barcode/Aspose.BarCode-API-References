---
title: MultyDecodeType
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Tipo di decodifica composito.
type: docs
weight: 200
url: /it/net/aspose.barcode.barcoderecognition/multydecodetype/
---
## MultyDecodeType class

Tipo di decodifica composito.

```csharp
public class MultyDecodeType : BaseDecodeType, IEquatable<MultyDecodeType>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MultyDecodeType](multydecodetype#constructor)(params BaseDecodeType[]) | Inizializza una nuova istanza di[`MultyDecodeType`](../multydecodetype) classe. |
| [MultyDecodeType](multydecodetype#constructor_1)(params SingleDecodeType[]) | Inizializza una nuova istanza di[`MultyDecodeType`](../multydecodetype) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multydecodetype/getsingletypescount) { get; } | Restituisce un numero di tipi singoli. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multydecodetype/add)(SingleDecodeType) | ne aggiunge un altro[`SingleDecodeType`](../singledecodetype)al MultyDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multydecodetype/containsall)(params BaseDecodeType[]) | Verifica se contiene tutti i tipi di codici a barre. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multydecodetype/containsany)(params BaseDecodeType[]) | Contiene uno qualsiasi dei tipi |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals)(BaseDecodeType) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`BaseDecodeType`](../basedecodetype) valore. |
| override [Equals](../../aspose.barcode.barcoderecognition/multydecodetype/equals#equals_1)(MultyDecodeType) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`MultyDecodeType`](../multydecodetype) valore. |
| override [Equals](../../aspose.barcode.barcoderecognition/multydecodetype/equals#equals_3)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`MultyDecodeType`](../multydecodetype) valore. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals)(SingleDecodeType) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato[`SingleDecodeType`](../singledecodetype) valore. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multydecodetype/gethashcode)() | Restituisce il codice hash per questa istanza. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multydecodetype/getsingletypes)() | Rappresenta un elenco di singoli tipi. |
| override [ToString](../../aspose.barcode.barcoderecognition/multydecodetype/tostring)() | Metodo sovrascritto che rappresenta MultyDecodeType come una stringa. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multydecodetype/tryparse)(string, out MultyDecodeType) | Converte la rappresentazione di stringa di un MultyDecodeType nella relativa istanza. Un valore restituito indica se la conversione è riuscita o meno. |

### Esempi

Questo esempio mostra come creare tipi MultiDecode composti che combinano tipi SingleDecodeType e MultiDecode.

```csharp
[C#]
MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.Code128, DecodeType.Code39Standard);
[VB.NET]
Dim multyType1 As MultyDecodeType 
multyType1 = New MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multyType2 As MultyDecodeType
multyType2 = New MultyDecodeType(multyType1, DecodeType.Code128, DecodeType.Code39Standard)
```

### Guarda anche

* class [BaseDecodeType](../basedecodetype)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
