---
title: "Aspose::BarCode::Generation::BarcodeGenerator clase"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::BarcodeGenerator clase. BarcodeGenerator para la generación de imágenes de códigos de barras en el backend en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Crea una instancia de [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Crea una instancia de [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Limpia cualquier recurso que se esté utilizando. |
| [ExportToXml](./exporttoxml/)(System::String) | Exporta las propiedades de [BarCode](../../aspose.barcode/) al archivo XML especificado |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporta las propiedades de [BarCode](../../aspose.barcode/) al flujo XML especificado |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genera la imagen del código de barras con la configuración actual. |
| [get_BarcodeType](./get_barcodetype/)() | Tipo de simbología de código de barras. |
| [get_CodeText](./get_codetext/)() | Texto a codificar. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parámetros. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importa las propiedades de [BarCode](../../aspose.barcode/) del archivo xml especificado y crea una instancia de [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importa las propiedades de [BarCode](../../aspose.barcode/) del flujo xml especificado y crea una instancia de [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Guarda la imagen del código de barras en un flujo en un formato específico. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Guarda la imagen del código de barras en un archivo específico en un formato específico. |
| [Save](./save/)(System::String) | Guarda la imagen del código de barras en un archivo específico. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Tipo de simbología de código de barras. |
| [set_CodeText](./set_codetext/)(System::String) | Texto a codificar. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Establece el texto del código como una secuencia de bytes. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Observaciones


simbologías compatibles: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Este ejemplo muestra cómo crear y guardar una imagen de código de barras.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
