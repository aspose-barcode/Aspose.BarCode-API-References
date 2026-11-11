---
title: "Clase BarCodeReader"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.BarCodeReader. BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras"
type: docs
weight: 70
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras.

```csharp
public class BarCodeReader : Component
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Inicializa una nueva instancia de la clase `BarCodeReader` con valores predeterminados. Requiere establecer la imagen (SetBitmapImage()) antes de llamar al método ReadBarCodes(). |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | Inicializa una nueva instancia de la clase `BarCodeReader` a partir de una imagen. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | Inicializa una nueva instancia de la clase `BarCodeReader` a partir de un cuadro de luminancia. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | Inicializa una nueva instancia de la clase `BarCodeReader` a partir de un archivo. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | Inicializa una nueva instancia de la clase `BarCodeReader`. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | Inicializa una nueva instancia de la clase `BarCodeReader`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Obtiene o establece el tipo de decodificación de código de barras usado para el reconocimiento. Debe establecerse antes de llamar a [`ReadBarCodes`](./readbarcodes/). |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Obtiene el array de [`BarCodeResult`](../barcoderesult/) reconocidos |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Obtiene el recuento de códigos de barras reconocidos |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Obtiene o establece el tiempo de espera del proceso de reconocimiento en milisegundos. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Obtiene la configuración del uso de núcleos del procesador. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Importa propiedades de BarCode desde el xml-stream especificado y las aplica a la instancia actual de BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Importa propiedades de BarCode desde el xml-file especificado y las aplica a la instancia actual de BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | La función solicita la terminación de la sesión de reconocimiento actual desde otro hilo. Abort es un método no bloqueable y devuelve el control justo después de llamarse. El método debe usarse cuando el proceso de reconocimiento es demasiado largo. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exporta propiedades de BarCode al xml-stream especificado |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exporta propiedades de BarCode al xml-file especificado |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Lee los [`BarCodeResult`](../barcoderesult/) de la imagen. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Establece la imagen bitmap para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Establece el marco de luminancia para el reconocimiento. Debe llamarse antes del método [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Establece la secuencia de imagen para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Establece el archivo de imagen para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Establece la imagen bitmap y el área para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Establece la imagen bitmap y las áreas para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Establece el marco de luminancia y el área para el reconocimiento. Debe llamarse antes del método [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Establece el marco de luminancia y las áreas para el reconocimiento. Debe llamarse antes del método [`ReadBarCodes`](./readbarcodes/). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Establece una matriz de tipo [`SingleDecodeType`](../singledecodetype/) para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |

## Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


