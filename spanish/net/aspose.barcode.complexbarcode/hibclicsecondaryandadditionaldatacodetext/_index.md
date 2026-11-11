---
title: "Clase HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.HIBCLICSecondaryAndAdditionalDataCodetext. Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos secundarios"
type: docs
weight: 590
url: /es/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos secundarios.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras. El codetext HIBC LIC puede codificarse usando los tipos de codificación HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC y HIBCQRLIC. Valor predeterminado: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Identifica datos suplementarios secundarios y adicionales. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Identifica el carácter de enlace. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICSecondaryAndAdditionalDataCodetext`. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Construye el codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Devuelve el código hash de esta instancia. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Inicializa la instancia a partir del codetext construido. |

## Ejemplos

Esta muestra muestra cómo codificar y decodificar HIBC LIC usando HIBCLICSecondaryAndAdditionalDataCodetext.

```csharp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

### Ver también

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


