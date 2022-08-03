---
title: SetBarCodeImage
second_title: Aspose.BarCode لمرجع .NET API
description: يضبط صورة نقطية للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes .
type: docs
weight: 110
url: /ar/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage}

يضبط صورة نقطية للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes ().

```csharp
public void SetBarCodeImage(Bitmap value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| value | Bitmap | الصورة النقطية للتعرف عليها. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_2}

يضبط الصورة النقطية ومناطق التعرف. يجب استدعاء قبل أسلوب ReadBarCodes ().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| value | Bitmap | الصورة النقطية للتعرف عليها. |
| areas | Rectangle[] | قائمة المناطق للاعتراف بها |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_1}

يضبط صورة نقطية ومنطقة للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes ().

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| value | Bitmap | الصورة النقطية للتعرف عليها. |
| area | Rectangle | منطقة للاعتراف |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_4}

تعيين ملف الصورة للتعرف عليه. يجب استدعاء قبل أسلوب ReadBarCodes ().

```csharp
public void SetBarCodeImage(string filename)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filename | String | ملف الصورة للتعرف. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_3}

يضبط دفق الصورة للتعرف عليها. يجب استدعاء قبل أسلوب ReadBarCodes ().

```csharp
public void SetBarCodeImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار الصورة للتعرف. |

### أمثلة

يوضح هذا النموذج كيفية اكتشاف الرموز الشريطية Code39 و Code128.

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

### أنظر أيضا

* class [BarCodeReader](../../barcodereader)
* مساحة الاسم [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* المجسم [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
