---
title: "Clase BarcodeGenerator"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.BarcodeGenerator. BarcodeGenerator para la generación de imágenes de códigos de barras en el backend"
type: docs
weight: 1000
url: /es/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator para la generación de imágenes de códigos de barras en el backend.

simbologías compatibles: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, código QR ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Crea una instancia de BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Crea una instancia de BarcodeGenerator. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Tipo de simbología de código de barras. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Texto a codificar. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Parámetros de generación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Importa las propiedades de BarCode desde el xml-stream especificado y crea una instancia de BarcodeGenerator. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Importa las propiedades de BarCode desde el xml-file especificado y crea una instancia de BarcodeGenerator. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Dibuja la imagen del código de barras en un lienzo WPF. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exporta propiedades de BarCode al xml-stream especificado |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exporta propiedades de BarCode al xml-file especificado |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Genera la imagen del código de barras con la configuración actual. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Guarda la imagen del código de barras en un archivo específico. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Guarda la imagen del código de barras en un flujo en un formato específico. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Guarda la imagen del código de barras en un archivo específico en un formato específico. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Establece codetext como una secuencia de bytes. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite, la función inserta automáticamente una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Codifica el Unicode **codeText** en una secuencia de bytes usando la **encoding** especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite y **insertBOM** está configurado a `true`, la función incluye una [marca de orden de bytes (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen de código de barras.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


