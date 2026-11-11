---
title: "Classe SecondaryAndAdditionalData"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData. Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC."
type: docs
weight: 770
url: /it/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC.

```csharp
public class SecondaryAndAdditionalData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifica la data di produzione. La data di produzione può essere impostata a DateTime.MinValue per non utilizzare questo campo. Valore predefinito: DateTime.MinValue. |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifica la data di scadenza. Verrà utilizzata se ExpiryDateFormat non è impostato su None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifica il formato della data di scadenza. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifica il numero di lotto o batch. Il numero di lotto/batch deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifica la quantità, deve essere un valore intero da 0 a 500. La quantità può essere impostata a -1 per non utilizzare questo campo. Valore predefinito: -1. |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifica il numero di serie. Il numero di serie deve essere una stringa alfanumerica con una lunghezza massima di 18 simboli. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Restituisce un valore che indica se questa istanza è uguale a un valore `SecondaryAndAdditionalData` specificato. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Restituisce il codice hash per questa istanza. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Istanzia i dati supplementari secondari e aggiuntivi dal formato stringa secondo la specifica HIBC LIC. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Converte i dati al formato stringa secondo la specifica HIBC LIC. |

### Vedi anche

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


