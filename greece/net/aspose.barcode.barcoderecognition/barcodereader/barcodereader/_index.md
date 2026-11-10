---
title: "BarCodeReader.BarCodeReader"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κατασκευαστής BarCodeReader. Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BarCodeReader με προεπιλεγμένες τιμές. Απαιτεί να οριστεί η εικόνα με SetBitmapImage πριν κληθεί η μέθοδος ReadBarCodes."
type: docs
weight: 10
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`BarCodeReader`](../) με προεπιλεγμένες τιμές. Απαιτεί να οριστεί η εικόνα (SetBitmapImage()) πριν κληθεί η μέθοδος ReadBarCodes().

```csharp
public BarCodeReader()
```

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_8}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../) από μια εικόνα.

```csharp
public BarCodeReader(Bitmap image)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Μια παρουσία Bitmap που περιέχει την εικόνα |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Δείτε επίσης

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα. |
| decodeTypes | BaseDecodeType[] | Τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης1. Μπορεί να είναι μοναδικός ή πολλαπλός |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα. |
| περιοχή | Rectangle | Η περιοχή για αναγνώριση. |
| decodeTypes | BaseDecodeType[] | Τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα. |
| περιοχή | Rectangle | Η περιοχή για αναγνώριση. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.Width, bmp.Height), new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle(0, 0, bmp.Width, bmp.Height), New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα για ανάγνωση |
| περιοχές | Rectangle[] | Ο πίνακας περιοχών αναγνώρισης |
| decodeTypes | BaseDecodeType[] | Οι τύποι αποκωδικοποίησης που εφαρμόζονται σε όλες τις καθορισμένες περιοχές. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, DecodeType.Code39, DecodeType.Code128)
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Bitmap | Η εικόνα για ανάγνωση |
| περιοχές | Rectangle[] | Ο πίνακας περιοχών αναγνώρισης |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης που εφαρμόζεται σε όλες τις καθορισμένες περιοχές. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.Width, bmp.Height) }, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using bmp = New Bitmap("c:\test.png")
    Using reader As New BarCodeReader(bmp, New Rectangle() {New Rectangle(0, 0, bmp.Width, bmp.Height)}, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../) από αρχείο.

```csharp
public BarCodeReader(string filename)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | String | Το όνομα αρχείου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | String | Το όνομα αρχείου. |
| decodeTypes | BaseDecodeType[] | Τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | String | Το όνομα αρχείου. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Η ροή. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr)
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode Type: " + result.CodeTypeName)
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Δείτε επίσης

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Η ροή. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, New MultiDecodeType(DecodeType.Code39, DecodeType.Code128))
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Η ροή. |
| decodeTypes | BaseDecodeType[] | Τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using fstr = New FileStream("c:\test.png", FileMode.Open)
    Using reader As New BarCodeReader(fstr, DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| περιοχές | Rectangle[] | Ο πίνακας περιοχών αναγνώρισης. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε καθορισμένες περιοχές ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| περιοχές | Rectangle[] | Ο πίνακας περιοχών αναγνώρισης. |
| decodeTypes | BaseDecodeType[] | Οι τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε καθορισμένες περιοχές ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader(frame, areas, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| περιοχή | Rectangle | Η περιοχή για αναγνώριση. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε μια καθορισμένη περιοχή ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| περιοχή | Rectangle | Η περιοχή για αναγνώριση. |
| decodeTypes | BaseDecodeType[] | Οι τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε μια καθορισμένη περιοχή ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle area = new Rectangle(0, 0, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, area, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| τύπος | BaseDecodeType | Ο τύπος αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε ένα πλαίσιο φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, new MultiDecodeType(DecodeType.Code39, DecodeType.Code128)))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`BarCodeReader`](../).

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |
| decodeTypes | BaseDecodeType[] | Οι τύποι αποκωδικοποίησης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε ένα πλαίσιο φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame, DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`BarCodeReader`](../) από ένα πλαίσιο φωτεινότητας.

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για ανάγνωση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε ένα πλαίσιο φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader(frame))
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
```

### Δείτε επίσης

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


