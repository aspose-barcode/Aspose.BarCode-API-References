---
title: "Klass HIBCPASCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.HIBCPASCodetext-klass. Klass för kodning och avkodning av text som är inbäddad i HIBC PAS-koden"
type: docs
weight: 600
url: /sv/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

Klass för kodning och avkodning av text som är inbäddad i HIBC PAS-koden.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstyp. HIBC PAS-codetext kan kodas med HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS och HIBCQRPAS kodningstyper. Standardvärde: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | Identifierar dataplats. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | Lägger till ny post |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | Lägger till ny post |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | Rensar postlista |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCPASCodetext`-värde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | Skapar kodtext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | Hämtar postlista |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man kodar och avkodar HIBC PAS med HIBCPASCodetext.

```csharp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText; 
		HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
		Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


