---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator clase"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator clase. ComplexBarcodeGenerator para generación de imágenes de códigos de barras complejos en el backend (p. ej., SwissQR) en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Crea una instancia de [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Limpia cualquier recurso que se esté utilizando. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genera una imagen de código de barras complejo con la configuración actual. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parámetros. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
| [Save](./save/)(System::String) | Genera y guarda una imagen de código de barras complejo con la configuración actual. |
## Observaciones


Este ejemplo muestra cómo crear y guardar una imagen SwissQR.
```cpp
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

## Ver también

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
