---
title: "método"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Ángulo de rotación de la imagen BarCode, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0 en C++."
type: docs
weight: 700
url: /es/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Observaciones


Este ejemplo muestra cómo crear y guardar una imagen [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Ver también

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
