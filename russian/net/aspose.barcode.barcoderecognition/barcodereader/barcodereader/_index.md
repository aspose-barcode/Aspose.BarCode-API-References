---
title: BarCodeReader
second_title: Справочник по API Aspose.BarCode для .NET
description: Инициализирует новый экземпляр классаBarCodeReaderaspose.barcode.barcoderecognition/barcodereaderсо значениями по умолчанию. Требуется установить изображение SetBitmapImage перед вызовом метода ReadBarCodes.
type: docs
weight: 10
url: /ru/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader)со значениями по умолчанию. Требуется установить изображение (SetBitmapImage()) перед вызовом метода ReadBarCodes().

```csharp
public BarCodeReader()
```

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader)из изображения.

```csharp
public BarCodeReader(Bitmap image)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Экземпляр растрового изображения, содержащий изображение |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение. |
| decodeTypes | BaseDecodeType[] | Типы декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение. |
| type | BaseDecodeType | Тип декодирования1. Он может быть одиночным или множественным |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение. |
| area | Rectangle | Область для распознавания. |
| decodeTypes | BaseDecodeType[] | Типы декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение. |
| area | Rectangle | Область для распознавания. |
| type | BaseDecodeType | Тип декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение для чтения |
| areas | Rectangle[] | Массив области распознавания |
| decodeTypes | BaseDecodeType[] | Типы декодирования применимы ко всем указанным областям. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | Bitmap | Изображение для чтения |
| areas | Rectangle[] | Массив области распознавания |
| type | BaseDecodeType | Тип декодирования применим ко всем указанным областям. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader)из файла.

```csharp
public BarCodeReader(string filename)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя_файла | String | Имя файла. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя_файла | String | Имя файла. |
| decodeTypes | BaseDecodeType[] | Типы декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя_файла | String | Имя файла. |
| type | BaseDecodeType | Тип декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| type | BaseDecodeType | Тип декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

Инициализирует новый экземпляр класса[`BarCodeReader`](../../barcodereader).

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |
| decodeTypes | BaseDecodeType[] | Типы декодирования. |

### Примеры

В этом примере показано, как обнаруживать штрих-коды Code39 и Code128.

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

### Смотрите также

* class [BaseDecodeType](../../basedecodetype)
* class [BarCodeReader](../../barcodereader)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* сборка [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
