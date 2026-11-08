---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters clase"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters clase. Almacena información de metadatos MacroPdf417 del código de barras reconocido en C++."
type: docs
weight: 2800
url: /es/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Almacena información de metadatos MacroPdf417 del código de barras reconocido.

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Indicador que indica que el código de barras MicroPdf417 está codificado con los códigos de emulación Code 128 908, 909, 910 o 911. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [get_IsLinked](./get_islinked/)() const | Indicador que indica que el código de barras debe estar vinculado a un código de barras 1D. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Utilizado para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nombre del destinatario Macro PDF417 (opcional). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Suma de verificación Macro PDF417 (opcional). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Obtiene el ID de archivo del código de barras, disponible solo con MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nombre de archivo Macro PDF417 (opcional). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Tamaño de archivo Macro PDF417 (opcional). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Obtiene el ID del segmento del código de barras, disponible solo con MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Obtiene el recuento de segmentos del código de barras macro pdf417. El valor predeterminado es -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nombre del remitente Macro PDF417 (opcional). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Indica si el segmento es el último segmento de un archivo Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Marca de tiempo Macro PDF417 (opcional). |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [Pdf417ExtendedParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener los metadatos Macro Pdf417.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
