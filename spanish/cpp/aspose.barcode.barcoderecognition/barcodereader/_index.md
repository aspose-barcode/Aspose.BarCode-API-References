---
title: "Clase Aspose::BarCode::BarCodeRecognition::BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::BarCodeReader. BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Abort](./abort/)() | La función solicita la terminación de la sesión de reconocimiento actual desde otro hilo. Abort es un método no bloqueable y devuelve el control justo después de llamarse. El método debe usarse cuando el proceso de reconocimiento es demasiado largo. |
| [BarCodeReader](./barcodereader/)() | Inicializa una nueva instancia de la clase [BarCodeReader](./) con valores predeterminados. Requiere establecer la imagen (SetBitmapImage()) antes de llamar al método [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./) a partir de una imagen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | Inicializa una nueva instancia de la clase [BarCodeReader](./) a partir de un archivo. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Inicializa una nueva instancia de la clase [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Inicializa una nueva instancia de la clase [BarCodeReader](./) a partir de un cuadro de luminancia. |
| [Dispose](./dispose/)() override | Liberar recurso |
| [ExportToXml](./exporttoxml/)(System::String) | Exporta las propiedades de [BarCode](../../aspose.barcode/) al archivo XML especificado |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporta las propiedades de [BarCode](../../aspose.barcode/) al flujo XML especificado |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Obtiene el tipo de decodificación de código de barras usado para el reconocimiento. Debe establecerse antes de llamar a [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | Los principales parámetros de decodificación de [BarCode](../../aspose.barcode/). Contiene parámetros que influyen en los datos reconocidos. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Obtiene la matriz de [BarCodeResult](../barcoderesult/) reconocidos |
| [get_FoundCount](./get_foundcount/)() | Obtiene el recuento de códigos de barras reconocidos |
| static [get_ProcessorSettings](./get_processorsettings/)() | Obtiene una configuración de uso de núcleos del procesador. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente [QualitySettings](../qualitysettings/) mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puedes configurar manualmente opciones separadas. El valor predeterminado de [QualitySettings](../qualitysettings/) es NormalQuality. |
| [get_Timeout](./get_timeout/)() | Obtiene el tiempo de espera del proceso de reconocimiento en milisegundos. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importa las propiedades de [BarCode](../../aspose.barcode/) desde el archivo XML especificado y las aplica a la instancia actual de [BarCodeReader](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importa las propiedades de [BarCode](../../aspose.barcode/) desde el flujo XML especificado y las aplica a la instancia actual de [BarCodeReader](./). |
| [ReadBarCodes](./readbarcodes/)() | Lee [BarCodeResult](../barcoderesult/)s de la imagen. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Establece el tipo de decodificación de código de barras utilizado para el reconocimiento. Debe establecerse antes de llamar a [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente [QualitySettings](../qualitysettings/) mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puedes configurar manualmente opciones separadas. El valor predeterminado de [QualitySettings](../qualitysettings/) es NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Establece el tiempo de espera del proceso de reconocimiento en milisegundos. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Establece la imagen bitmap para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Establece la imagen bitmap y las áreas para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Establece la imagen bitmap y el área para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Establece el archivo de imagen para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Establece el flujo de imagen para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Establece el marco de luminancia y el área para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Establece el marco de luminancia y las áreas para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Establece el marco de luminancia para el reconocimiento. Debe llamarse antes del método [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Establece la matriz de tipos [SingleDecodeType](../singledecodetype/) para el reconocimiento. Debe llamarse antes del método [ReadBarCodes()](./readbarcodes/). |
## Observaciones


Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.
```cpp
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

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
