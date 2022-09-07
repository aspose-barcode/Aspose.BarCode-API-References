---
title: BarCodeReader
second_title: Referencia de API de Aspose.BarCode para .NET
description: Inicializa una nueva instancia delBarCodeReaderaspose.barcode.barcoderecognition/barcodereader clase con valores predeterminados. Requiere configurar la imagen SetBitmapImage antes de llamar al método ReadBarCodes.
type: docs
weight: 10
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase con valores predeterminados. Requiere configurar la imagen (SetBitmapImage()) antes de llamar al método ReadBarCodes().

```csharp
public BarCodeReader()
```

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase de una imagen.

```csharp
public BarCodeReader(Bitmap image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | Una instancia de mapa de bits que contiene la imagen |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen. |
| decodeTypes | BaseDecodeType[] | Tipos de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen. |
| type | BaseDecodeType | El tipo de decodificación1. Puede ser individual o multi |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen. |
| area | Rectangle | El área de reconocimiento. |
| decodeTypes | BaseDecodeType[] | Tipos de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen. |
| area | Rectangle | El área de reconocimiento. |
| type | BaseDecodeType | El tipo de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen para leer |
| areas | Rectangle[] | La variedad de áreas de reconocimiento. |
| decodeTypes | BaseDecodeType[] | Los tipos de decodificación aplicables para todas las áreas especificadas. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39Standard, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Bitmap | La imagen para leer |
| areas | Rectangle[] | La variedad de áreas de reconocimiento. |
| type | BaseDecodeType | El tipo de decodificación aplicable para todas las áreas especificadas. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase del archivo.

```csharp
public BarCodeReader(string filename)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo. |
| decodeTypes | BaseDecodeType[] | Tipos de decodificación. |

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

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo. |
| type | BaseDecodeType | El tipo de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| type | BaseDecodeType | El tipo de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultyDecodeType(DecodeType.Code39Standard, DecodeType.Code128))
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Inicializa una nueva instancia del[`BarCodeReader`](../../barcodereader) clase.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| decodeTypes | BaseDecodeType[] | Tipos de decodificación. |

### Ejemplos

Este ejemplo muestra cómo detectar códigos de barras Code39 y Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39Standard, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Ver también

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
