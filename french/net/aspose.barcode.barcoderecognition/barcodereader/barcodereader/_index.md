---
title: BarCodeReader
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Initialise une nouvelle instance duBarCodeReaderaspose.barcode.barcoderecognition/barcodereader classe avec les valeurs par défaut. Nécessite de définir limage SetBitmapImage avant dappeler la méthode ReadBarCodes.
type: docs
weight: 10
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe avec les valeurs par défaut. Nécessite de définir l'image (SetBitmapImage()) avant d'appeler la méthode ReadBarCodes().

```csharp
public BarCodeReader()
```

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe à partir d'une image.

```csharp
public BarCodeReader(Bitmap image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | Une instance Bitmap contenant l'image |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image. |
| decodeTypes | BaseDecodeType[] | Décoder les types. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image. |
| type | BaseDecodeType | Le type de décodage1. Il peut être simple ou multiple |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image. |
| area | Rectangle | Le domaine de la reconnaissance. |
| decodeTypes | BaseDecodeType[] | Décoder les types. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image. |
| area | Rectangle | Le domaine de la reconnaissance. |
| type | BaseDecodeType | Le type de décodage. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image à lire |
| areas | Rectangle[] | L'éventail des zones de reconnaissance |
| decodeTypes | BaseDecodeType[] | Les types de décodage applicables pour toutes les zones spécifiées. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | Bitmap | L'image à lire |
| areas | Rectangle[] | L'éventail des zones de reconnaissance |
| type | BaseDecodeType | Le type de décodage applicable pour toutes les zones spécifiées. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe du fichier.

```csharp
public BarCodeReader(string filename)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filename | String | Le nom du fichier. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filename | String | Le nom du fichier. |
| decodeTypes | BaseDecodeType[] | Décoder les types. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filename | String | Le nom du fichier. |
| type | BaseDecodeType | Le type de décodage. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| type | BaseDecodeType | Le type de décodage. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Initialise une nouvelle instance du[`BarCodeReader`](../../barcodereader) classe.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| decodeTypes | BaseDecodeType[] | Décoder les types. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

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

### Voir également

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
