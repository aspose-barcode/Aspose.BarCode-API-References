---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método BarcodeGenerator. Genera la imagen del código de barras con la configuración actual"
type: docs
weight: 80
url: /es/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Genera la imagen del código de barras con la configuración actual.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Valor de retorno

Imagen de código de barras. Ver Bitmap.

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen de código de barras.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Ver también

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


