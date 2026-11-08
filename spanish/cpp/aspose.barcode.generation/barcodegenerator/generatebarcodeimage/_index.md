---
title: "método"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Generar la imagen del código de barras con la configuración actual en C++."
type: docs
weight: 800
url: /es/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Genera la imagen del código de barras con la configuración actual.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Imagen de código de barras. Ver [Bitmap](../).
## Observaciones



Este ejemplo muestra cómo crear y guardar una imagen de código de barras.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Ver también

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
