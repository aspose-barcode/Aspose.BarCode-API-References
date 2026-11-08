---
title: "Clase Aspose::BarCode::BarCodeRecognition::QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::QRExtendedParameters. Almacena información de Structured Append de QR del código de barras reconocido en C++."
type: docs
weight: 2900
url: /es/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Almacena información de Structured Append de [QR](../../aspose.barcode.barcoderecognition.qr/) del código de barras reconocido

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** si todos los parámetros tienen solo valores predeterminados |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versión del MicroQR Code reconocido. De M1 a M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Versión del RectMicroQR Code reconocido. De R7x43 a R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Obtiene el índice del código de barras en modo structured append de [QR](../../aspose.barcode.barcoderecognition.qr/). El índice comienza en 0. El valor predeterminado es -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Obtiene la cantidad de códigos de barras en modo structured append de [QR](../../aspose.barcode.barcoderecognition.qr/). El valor predeterminado es -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Obtiene los datos de paridad del modo structured append de [QR](../../aspose.barcode.barcoderecognition.qr/). El valor predeterminado es -1. |
| [get_Version](./get_version/)() const | Versión del [QR](../../aspose.barcode.barcoderecognition.qr/) Code reconocido. De Version1 a Version40. |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [QRExtendedParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener los datos de Structured Append de [QR](../../aspose.barcode.barcoderecognition.qr/)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## Ver también

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
