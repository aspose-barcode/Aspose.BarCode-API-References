---
title: BarCodeReader
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: क एक नय उदहरण प्ररंभ करत हैBarCodeReaderaspose.barcode.barcoderecognition/barcodereader/ वर्ग डफ़ल्ट मन के सथ
type: docs
weight: 10
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग डिफ़ॉल्ट मान के साथ।

```csharp
public BarCodeReader()
```

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) एक छवि से वर्ग.

```csharp
public BarCodeReader(Bitmap image)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | एक बिटमैप उदाहरण जिसमें छवि है |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | छवि। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | छवि। |
| type | BaseDecodeType | डिकोड टाइप 1। यह सिंगल या मल्टी हो सकता है |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | छवि। |
| area | Rectangle | मान्यता के लिए क्षेत्र। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | छवि। |
| area | Rectangle | मान्यता के लिए क्षेत्र। |
| type | BaseDecodeType | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | पढ़ने के लिए छवि |
| areas | Rectangle[] | मान्यता क्षेत्रों की सरणी |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार निर्दिष्ट सभी क्षेत्रों के लिए लागू होते हैं। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | Bitmap | पढ़ने के लिए छवि |
| areas | Rectangle[] | मान्यता क्षेत्रों की सरणी |
| type | BaseDecodeType | डिकोड प्रकार निर्दिष्ट सभी क्षेत्रों के लिए लागू होता है। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) फ़ाइल से वर्ग.

```csharp
public BarCodeReader(string filename)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | String | फ़ाइल नाम। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | String | फ़ाइल नाम। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | String | फ़ाइल नाम। |
| type | BaseDecodeType | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | धारा। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | धारा। |
| type | BaseDecodeType | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

का एक नया उदाहरण प्रारंभ करता है[`BarCodeReader`](../) वर्ग.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | धारा। |
| decodeTypes | BaseDecodeType[] | डिकोड प्रकार। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

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

### यह सभी देखें

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
