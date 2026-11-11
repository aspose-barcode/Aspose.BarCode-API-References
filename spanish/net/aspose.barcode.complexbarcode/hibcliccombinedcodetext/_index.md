---
title: "Clase HIBCLICCombinedCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.HIBCLICCombinedCodetext. Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios"
type: docs
weight: 550
url: /es/net/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios y secundarios.

```csharp
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HIBCLICCombinedCodetext](hibcliccombinedcodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras. El codetext HIBC LIC puede codificarse usando los tipos de codificación HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC y HIBCQRLIC. Valor predeterminado: HIBCCode39LIC. |
| [PrimaryData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/primarydata/) { get; set; } | Identifica los datos primarios. |
| [SecondaryAndAdditionalData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/secondaryandadditionaldata/) { get; set; } | Identifica los datos secundarios y complementarios adicionales. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICCombinedCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/getconstructedcodetext/)() | Construye el codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/initfromstring/)(string) | Inicializa la instancia a partir del codetext construido. |

## Ejemplos

Este ejemplo muestra cómo codificar y decodificar HIBC LIC usando HIBCLICCombinedCodetext.

```csharp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

### Ver también

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


