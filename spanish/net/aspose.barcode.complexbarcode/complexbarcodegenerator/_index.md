---
title: "Clase ComplexBarcodeGenerator"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator. ComplexBarcodeGenerator para la generación de códigos de barras complejos en el backend, p. ej., generación de imágenes SwissQR"
type: docs
weight: 510
url: /es/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator para la generación de imágenes de códigos de barras complejos en el backend (p. ej., SwissQR).

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Crea una instancia de ComplexBarcodeGenerator. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Parámetros de generación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Genera una imagen de código de barras complejo con la configuración actual. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen SwissQR.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // inicializa el resto de los campos
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Ver también

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


