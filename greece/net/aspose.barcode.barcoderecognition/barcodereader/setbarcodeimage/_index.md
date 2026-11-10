---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Μέθοδος BarCodeReader. Ορίζει την εικόνα bitmap για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes."
type: docs
weight: 120
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

Ορίζει την bitmap εικόνα για την αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για την αναγνώριση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

Ορίζει την bitmap εικόνα και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για την αναγνώριση. |
| περιοχές | Rectangle[] | λίστα περιοχών για αναγνώριση |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

Ορίζει την bitmap εικόνα και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Bitmap | Η εικόνα bitmap για την αναγνώριση. |
| περιοχή | Rectangle | περιοχή για αναγνώριση |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (Bitmap bmp = new Bitmap(@"c:\test.png"))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

Ορίζει το αρχείο εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(string filename)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | String | Το αρχείο εικόνας για την αναγνώριση. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

Ορίζει τη ροή εικόνας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes().

```csharp
public void SetBarCodeImage(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Η ροή εικόνας για την αναγνώριση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128.

```csharp
[C#]
using (FileStream fstr = new FileStream(@"c:\test.png", FileMode.Open))
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
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
        reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
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
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

Ορίζει το πλαίσιο φωτεινότητας και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για την αναγνώριση. |
| περιοχή | Rectangle | Η περιοχή για αναγνώριση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε μια καθορισμένη περιοχή ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, new Rectangle(0, 0, width, height));
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

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

Ορίζει το πλαίσιο φωτεινότητας και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για την αναγνώριση. |
| περιοχές | Rectangle[] | Ο πίνακας περιοχών αναγνώρισης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε καθορισμένες περιοχές ενός πλαισίου φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height);
Rectangle[] areas = { new Rectangle(0, 0, width, height / 2), new Rectangle(0, height / 2, width, height / 2) };

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame, areas);
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

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

Ορίζει το πλαίσιο φωτεινότητας για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [`ReadBarCodes`](../readbarcodes/).

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | LuminanceFrame | Το πλαίσιο φωτεινότητας για την αναγνώριση. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να εντοπίσετε γραμμωτούς κώδικες Code39 και Code128 σε ένα πλαίσιο φωτεινότητας.

```csharp
int width = 1920;
int height = 1080;
int rowStride = 2048;
byte[] data = GetLuminanceData();
LuminanceFrame frame = new LuminanceFrame(data, width, height, rowStride, 90);

using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(frame);
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


