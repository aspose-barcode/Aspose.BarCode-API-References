---
title: BarCodeReader
second_title: Referencia de API de Aspose.BarCode para .NET
description: BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras luego puede realizar la operación ReadBarCodes para detectar códigos de barras.
type: docs
weight: 60
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, luego puede realizar la operación ReadBarCodes para detectar códigos de barras.

```csharp
public class BarCodeReader : Component
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase con valores predeterminados. Requiere configurar la imagen (SetBitmapImage()) antes de llamar al método ReadBarCodes(). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase de una imagen. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase del archivo. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Inicializa una nueva instancia del[`BarCodeReader`](../barcodereader) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Se reconoce[`BarCodeResult`](../barcoderesult)matriz s |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Obtiene el recuento de códigos de barras reconocidos |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings permite configurar manualmente la calidad y la velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante ajustes preestablecidos integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Obtiene o establece el tiempo de espera del proceso de reconocimiento en milisegundos. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Obtiene una configuración de uso de núcleos de procesador. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Importa las propiedades de BarCode del flujo xml especificado y las aplica a la instancia actual de BarCodeReader. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Importa las propiedades de BarCode del archivo xml especificado y las aplica a la instancia actual de BarCodeReader. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | La función solicita la finalización de la sesión de reconocimiento actual de otro subproceso. Abortar es un método desbloqueable y devuelve el control justo después de llamar. El método debe usarse cuando el proceso de reconocimiento es demasiado largo. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Exporta propiedades de código de barras al flujo xml especificado |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Exporta las propiedades del código de barras al archivo xml especificado |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | Lecturas[`BarCodeResult`](../barcoderesult) s de la imagen. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Establece la imagen de mapa de bits para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Establece el flujo de imágenes para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Establece el archivo de imagen para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Establece la imagen de mapa de bits y el área de reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Establece la imagen de mapa de bits y las áreas de reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Establece el tipo de decodificación para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Conjuntos[`SingleDecodeType`](../singledecodetype) matriz de tipos para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
