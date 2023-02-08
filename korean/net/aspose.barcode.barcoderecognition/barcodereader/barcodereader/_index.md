---
title: BarCodeReader
second_title: .NET API 참조용 Aspose.BarCode
description: 의 새 인스턴스를 초기화합니다.BarCodeReaderaspose.barcode.barcoderecognition/barcodereader/ 기본값이 있는 클래스. ReadBarCodes 메서드를 호출하기 전에 이미지SetBitmapImage를 설정해야 합니다.
type: docs
weight: 10
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 기본값이 있는 클래스. ReadBarCodes() 메서드를 호출하기 전에 이미지(SetBitmapImage())를 설정해야 합니다.

```csharp
public BarCodeReader()
```

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) image. 의 클래스

```csharp
public BarCodeReader(Bitmap image)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 이미지를 포함하는 Bitmap 인스턴스 |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 이미지. |
| decodeTypes | BaseDecodeType[] | 유형을 디코딩합니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 이미지. |
| type | BaseDecodeType | 디코드 유형1. 단일 또는 다중일 수 있습니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 이미지. |
| area | Rectangle | 인식 영역입니다. |
| decodeTypes | BaseDecodeType[] | 유형을 디코딩합니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 이미지. |
| area | Rectangle | 인식 영역입니다. |
| type | BaseDecodeType | 디코드 유형입니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 읽을 이미지 |
| areas | Rectangle[] | 인식 영역의 배열 |
| decodeTypes | BaseDecodeType[] | 지정된 모든 영역에 적용 가능한 디코드 유형입니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | Bitmap | 읽을 이미지 |
| areas | Rectangle[] | 인식 영역의 배열 |
| type | BaseDecodeType | 지정된 모든 영역에 적용 가능한 디코드 유형입니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_11}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) file. 의 클래스

```csharp
public BarCodeReader(string filename)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filename | String | 파일 이름. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_13}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filename | String | 파일 이름. |
| decodeTypes | BaseDecodeType[] | 유형을 디코딩합니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_12}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filename | String | 파일 이름. |
| type | BaseDecodeType | 디코드 유형입니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_9}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |
| type | BaseDecodeType | 디코드 유형입니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_10}

의 새 인스턴스를 초기화합니다.[`BarCodeReader`](../) 클래스.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 스트림. |
| decodeTypes | BaseDecodeType[] | 유형을 디코딩합니다. |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 집회 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
