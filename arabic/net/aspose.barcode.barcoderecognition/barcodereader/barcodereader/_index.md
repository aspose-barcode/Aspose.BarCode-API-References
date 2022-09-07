---
title: BarCodeReader
second_title: Aspose.BarCode لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفBarCodeReaderaspose.barcode.barcoderecognition/barcodereader فئة مع القيم الافتراضية . يتطلب تعيين الصورة SetBitmapImage  قبل استدعاء طريقة ReadBarCodes .
type: docs
weight: 10
url: /ar/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة مع القيم الافتراضية . يتطلب تعيين الصورة (SetBitmapImage ()) قبل استدعاء طريقة ReadBarCodes ().

```csharp
public BarCodeReader()
```

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة من صورة.

```csharp
public BarCodeReader(Bitmap image)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | مثيل Bitmap يحتوي على الصورة |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة. |
| decodeTypes | BaseDecodeType[] | أنواع فك. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة. |
| type | BaseDecodeType | نوع فك التشفير 1. يمكن أن تكون مفردة أو متعددة |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة. |
| area | Rectangle | مجال الاعتراف. |
| decodeTypes | BaseDecodeType[] | أنواع فك. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة. |
| area | Rectangle | مجال الاعتراف. |
| type | BaseDecodeType | نوع فك الشفرة. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة للقراءة |
| areas | Rectangle[] | مجموعة مجالات التعرف |
| decodeTypes | BaseDecodeType[] | أنواع فك الشفرة المطبقة على جميع المناطق المحددة. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | Bitmap | الصورة للقراءة |
| areas | Rectangle[] | مجموعة مجالات التعرف |
| type | BaseDecodeType | نوع فك الشفرة المطبق على جميع المناطق المحددة. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة من ملف .

```csharp
public BarCodeReader(string filename)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filename | String | اسم الملف. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filename | String | اسم الملف. |
| decodeTypes | BaseDecodeType[] | أنواع فك. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filename | String | اسم الملف. |
| type | BaseDecodeType | نوع فك الشفرة. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |
| type | BaseDecodeType | نوع فك الشفرة. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

يقوم بتهيئة مثيل جديد لملف[`BarCodeReader`](../../barcodereader) فئة .

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق. |
| decodeTypes | BaseDecodeType[] | أنواع فك. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
