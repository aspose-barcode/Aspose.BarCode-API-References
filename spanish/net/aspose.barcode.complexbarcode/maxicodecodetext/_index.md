---
title: "Clase MaxiCodeCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext. Clase base para codificar y decodificar el texto incrustado en el código MaxiCode"
type: docs
weight: 680
url: /es/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

Clase base para codificar y decodificar el texto incrustado en el código MaxiCode.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Obtiene o establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Obtiene o establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Construye el codetext |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Obtiene el modo MaxiCode. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Inicializa la instancia a partir del codetext construido. |

## Ejemplos

Este ejemplo muestra cómo decodificar el texto bruto de MaxiCode a una instancia de MaxiCodeCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


