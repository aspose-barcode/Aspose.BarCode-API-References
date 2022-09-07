---
title: BarCodeReader
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Inizializza una nuova istanza diBarCodeReaderaspose.barcode.barcoderecognition/barcodereader classe con valori predefiniti. Richiede di impostare limmagine SetBitmapImage prima di chiamare il metodo ReadBarCodes.
type: docs
weight: 10
url: /it/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe con valori predefiniti. Richiede di impostare l'immagine (SetBitmapImage()) prima di chiamare il metodo ReadBarCodes().

```csharp
public BarCodeReader()
```

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe da un'immagine.

```csharp
public BarCodeReader(Bitmap image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | Un'istanza Bitmap contenente l'immagine |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine. |
| decodeTypes | BaseDecodeType[] | Tipi di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine. |
| type | BaseDecodeType | Il tipo di decodifica1. Può essere singolo o multiplo |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine. |
| area | Rectangle | L'area per il riconoscimento. |
| decodeTypes | BaseDecodeType[] | Tipi di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine. |
| area | Rectangle | L'area per il riconoscimento. |
| type | BaseDecodeType | Il tipo di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine da leggere |
| areas | Rectangle[] | La matrice delle aree di riconoscimento |
| decodeTypes | BaseDecodeType[] | tipi di decodifica applicabili a tutte le aree specificate. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Bitmap | L'immagine da leggere |
| areas | Rectangle[] | La matrice delle aree di riconoscimento |
| type | BaseDecodeType | Il tipo di decodifica applicabile a tutte le aree specificate. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe dal file.

```csharp
public BarCodeReader(string filename)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file. |
| decodeTypes | BaseDecodeType[] | Tipi di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | String | Il nome del file. |
| type | BaseDecodeType | Il tipo di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| type | BaseDecodeType | Il tipo di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Inizializza una nuova istanza di[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso. |
| decodeTypes | BaseDecodeType[] | Tipi di decodifica. |

### Esempi

Questo esempio mostra come rilevare i codici a barre Code39 e Code128.

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

### Guarda anche

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* assemblea [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
