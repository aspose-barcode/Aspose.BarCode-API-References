---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Constructor LuminanceFrame. Inicializa una nueva instancia de la clase LuminanceFrame sin relleno entre filas. La distancia entre filas adyacentes es igual a width"
type: docs
weight: 10
url: /es/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Inicializa una nueva instancia de la clase [`LuminanceFrame`](../) sin relleno entre filas. La distancia entre filas adyacentes es igual a *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | Byte[] | Los datos de luminancia que contienen un byte por píxel. |
| width | Int32 | El ancho del fotograma en píxeles. |
| height | Int32 | La altura del fotograma en píxeles. |
| rotationDegrees | Int32 | La rotación en sentido horario necesaria para mostrar el fotograma en posición vertical. Los valores admitidos son 0, 90, 180 y 270. El valor predeterminado es 0. |

### Ver también

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Inicializa una nueva instancia de la clase [`LuminanceFrame`](../) con el paso de fila especificado.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | Byte[] | Los datos de luminancia que contienen un byte por píxel. |
| width | Int32 | El ancho del fotograma en píxeles. |
| height | Int32 | La altura del fotograma en píxeles. |
| rowStride | Int32 | La distancia en bytes entre los comienzos de dos filas adyacentes. El valor no puede ser menor que *width*. |
| rotationDegrees | Int32 | La rotación en sentido horario requerida para mostrar el fotograma en posición vertical. Los valores admitidos son 0, 90, 180 y 270. |

### Ver también

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


