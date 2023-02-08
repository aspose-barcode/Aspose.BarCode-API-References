---
title: BarCodeReader
second_title: Aspose.BarCode για Αναφορά API .NET
description: Αρχικοποιεί μια νέα παρουσία τουBarCodeReaderaspose.barcode.barcoderecognition/barcodereader/ κλάση με προεπιλεγμένες τιμές. Απαιτεί να ορίσετε την εικόνα SetBitmapImage πριν να καλέσετε τη μέθοδο ReadBarCodes.
type: docs
weight: 10
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) κλάση με προεπιλεγμένες τιμές. Απαιτεί να ορίσετε την εικόνα (SetBitmapImage()) πριν να καλέσετε τη μέθοδο ReadBarCodes().

```csharp
public BarCodeReader()
```

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

## BarCodeReader(Bitmap) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη από εικόνα.

```csharp
public BarCodeReader(Bitmap image)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Ένα στιγμιότυπο Bitmap που περιέχει την εικόνα |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα. |
| decodeTypes | BaseDecodeType[] | Αποκωδικοποίηση τύπων. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα. |
| type | BaseDecodeType | Ο τύπος αποκωδικοποίησης 1. Μπορεί να είναι μονή ή πολλαπλή |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα. |
| area | Rectangle | Η περιοχή για την αναγνώριση. |
| decodeTypes | BaseDecodeType[] | Αποκωδικοποίηση τύπων. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα. |
| area | Rectangle | Η περιοχή για την αναγνώριση. |
| type | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα για ανάγνωση |
| areas | Rectangle[] | Η σειρά των περιοχών αναγνώρισης |
| decodeTypes | BaseDecodeType[] | Οι τύποι αποκωδικοποίησης που ισχύουν για όλες τις περιοχές που καθορίζονται. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | Bitmap | Η εικόνα για ανάγνωση |
| areas | Rectangle[] | Η σειρά των περιοχών αναγνώρισης |
| type | BaseDecodeType | Ο τύπος αποκωδικοποίησης που ισχύει για όλες τις περιοχές που καθορίζονται. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη από αρχείο.

```csharp
public BarCodeReader(string filename)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | String | Το όνομα αρχείου. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | String | Το όνομα αρχείου. |
| decodeTypes | BaseDecodeType[] | Αποκωδικοποίηση τύπων. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | String | Το όνομα αρχείου. |
| type | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα. |
| type | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Αρχικοποιεί μια νέα παρουσία του[`BarCodeReader`](../) τάξη.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα. |
| decodeTypes | BaseDecodeType[] | Αποκωδικοποίηση τύπων. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να ανιχνεύσετε τους γραμμωτούς κώδικες Code39 και Code128.

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

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
