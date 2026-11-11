---
title: "Clase HIBCLICPrimaryDataCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.HIBCLICPrimaryDataCodetext. Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios"
type: docs
weight: 580
url: /es/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras. El codetext HIBC LIC puede codificarse usando los tipos de codificación HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC y HIBCQRLIC. Valor predeterminado: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Identifica los datos primarios. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICPrimaryDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Construye el codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Inicializa la instancia a partir del codetext construido. |

## Ejemplos

Este ejemplo muestra cómo codificar y decodificar HIBC LIC usando HIBCLICPrimaryDataCodetext.

```csharp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### Ver también

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


