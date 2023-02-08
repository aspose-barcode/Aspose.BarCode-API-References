---
title: SetBarCodeImage
second_title: Aspose.BarCode για Αναφορά API .NET
description: Ορίζει την εικόνα bitmap για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes.
type: docs
weight: 110
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

Ορίζει την εικόνα bitmap για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για αναγνώριση. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

Ορίζει την εικόνα bitmap και τις περιοχές για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για αναγνώριση. |
| areas | Rectangle[] | λίστα περιοχών για αναγνώριση |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

Ορίζει την εικόνα bitmap και την περιοχή για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για αναγνώριση. |
| area | Rectangle | περιοχή για αναγνώριση |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

Ορίζει το αρχείο εικόνας για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(string filename)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | String | Το αρχείο εικόνας για αναγνώριση. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

Ρυθμίζει τη ροή εικόνας για αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή εικόνας για αναγνώριση. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
