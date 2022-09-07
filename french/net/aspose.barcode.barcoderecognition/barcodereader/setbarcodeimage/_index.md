---
title: SetBarCodeImage
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Définit limage bitmap pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes.
type: docs
weight: 110
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Définit l'image bitmap pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| value | Bitmap | L'image bitmap pour la reconnaissance. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp)
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

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Définit l'image bitmap et les zones de reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| value | Bitmap | L'image bitmap pour la reconnaissance. |
| areas | Rectangle[] | liste des domaines pour la reconnaissance |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) });
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)})
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

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Définit l'image bitmap et la zone de reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| value | Bitmap | L'image bitmap pour la reconnaissance. |
| area | Rectangle | espace de reconnaissance |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height));
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height))
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

## SetBarCodeImage(string) {#setbarcodeimage_4}

Définit le fichier image pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(string filename)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filename | String | Le fichier image pour la reconnaissance. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Définit le flux d'images pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

```csharp
public void SetBarCodeImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux d'images pour la reconnaissance. |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128);
    reader.SetBarCodeImage(fstr);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader()
        reader.SetBarCodeReadType(DecodeType.Code39Standard, DecodeType.Code128)
        reader.SetBarCodeImage(fstr)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
