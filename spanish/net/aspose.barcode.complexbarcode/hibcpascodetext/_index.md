---
title: "Clase HIBCPASCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.HIBCPASCodetext. Clase para codificar y decodificar el texto incrustado en el código HIBC PAS"
type: docs
weight: 600
url: /es/net/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC PAS.

```csharp
public class HIBCPASCodetext : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HIBCPASCodetext](hibcpascodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras. El codetext HIBC PAS puede codificarse usando HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS y HIBCQRPAS. Valor predeterminado: HIBCCode39PAS. |
| [DataLocation](../../aspose.barcode.complexbarcode/hibcpascodetext/datalocation/) { get; set; } | Identifica la ubicación de los datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord_1)(HIBCPASRecord) | Agrega un nuevo registro |
| [AddRecord](../../aspose.barcode.complexbarcode/hibcpascodetext/addrecord/#addrecord)(HIBCPASDataType, string) | Agrega un nuevo registro |
| [Clear](../../aspose.barcode.complexbarcode/hibcpascodetext/clear/)() | Borra la lista de registros |
| override [Equals](../../aspose.barcode.complexbarcode/hibcpascodetext/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCPASCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcpascodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcpascodetext/getconstructedcodetext/)() | Construye el codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcpascodetext/gethashcode/)() | Devuelve el código hash de esta instancia. |
| [GetRecords](../../aspose.barcode.complexbarcode/hibcpascodetext/getrecords/)() | Obtiene la lista de registros |
| [InitFromString](../../aspose.barcode.complexbarcode/hibcpascodetext/initfromstring/)(string) | Inicializa la instancia a partir del codetext construido. |

## Ejemplos

Este ejemplo muestra cómo codificar y decodificar HIBC PAS usando HIBCPASCodetext.

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

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


