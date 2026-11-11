---
title: "Klass SecondaryAndAdditionalData"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData klass. Klass för lagring av sekundär och ytterligare HIBC LIC-data"
type: docs
weight: 770
url: /sv/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Klass för lagring av sekundär och ytterligare HIBC LIC-data.

```csharp
public class SecondaryAndAdditionalData
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifierar format för utgångsdatum. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifierar parti- eller batchnummer. Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken. . |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng på upp till 18 tecken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `SecondaryAndAdditionalData`-värde. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Instansierar sekundära och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |

### Se även

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


