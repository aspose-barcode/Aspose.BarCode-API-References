---
title: "BarCodeReader.BarCodeReader"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 생성자. 기본값으로 BarCodeReader 클래스의 새 인스턴스를 초기화한다. ReadBarCodes 메서드를 호출하기 전에 이미지 SetBitmapImage를 설정해야 한다."
type: docs
weight: 10
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/barcodereader/
---
## BarCodeReader() {#constructor}

기본값으로 [`BarCodeReader`](../) 클래스의 새 인스턴스를 초기화한다. ReadBarCodes() 메서드를 호출하기 전에 이미지 (SetBitmapImage())를 설정해야 한다.

```csharp
public BarCodeReader()
```

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap) {#constructor_8}

이미지에서 [`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 이미지를 포함하는 Bitmap 인스턴스 |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, params BaseDecodeType[]) {#constructor_10}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 이미지. |
| decodeTypes | BaseDecodeType[] | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, BaseDecodeType) {#constructor_9}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 이미지. |
| type | BaseDecodeType | 디코드 유형1. 단일 또는 다중일 수 있습니다. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, params BaseDecodeType[]) {#constructor_12}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 이미지. |
| area | Rectangle | 인식 영역. |
| decodeTypes | BaseDecodeType[] | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle, BaseDecodeType) {#constructor_11}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, Rectangle area, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 이미지. |
| area | Rectangle | 인식 영역. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], params BaseDecodeType[]) {#constructor_14}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 읽을 이미지 |
| areas | Rectangle[] | 인식 영역 배열 |
| decodeTypes | BaseDecodeType[] | 지정된 모든 영역에 적용되는 디코드 유형들. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Bitmap, Rectangle[], BaseDecodeType) {#constructor_13}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Bitmap image, Rectangle[] areas, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | Bitmap | 읽을 이미지 |
| areas | Rectangle[] | 인식 영역 배열 |
| type | BaseDecodeType | 지정된 모든 영역에 적용되는 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string) {#constructor_18}

파일에서 [`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(string filename)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | 파일 이름. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, params BaseDecodeType[]) {#constructor_20}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(string filename, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | 파일 이름. |
| decodeTypes | BaseDecodeType[] | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(string, BaseDecodeType) {#constructor_19}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(string filename, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | 파일 이름. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream) {#constructor_15}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, BaseDecodeType) {#constructor_16}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Stream stream, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(Stream, params BaseDecodeType[]) {#constructor_17}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(Stream stream, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 스트림. |
| decodeTypes | BaseDecodeType[] | 디코드 유형. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], BaseDecodeType) {#constructor_6}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| areas | Rectangle[] | 인식 영역 배열입니다. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle[], params BaseDecodeType[]) {#constructor_7}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle[] areas, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| areas | Rectangle[] | 인식 영역 배열입니다. |
| decodeTypes | BaseDecodeType[] | 디코드 유형입니다. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, BaseDecodeType) {#constructor_4}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| area | Rectangle | 인식 영역. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, Rectangle, params BaseDecodeType[]) {#constructor_5}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, Rectangle area, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| area | Rectangle | 인식 영역. |
| decodeTypes | BaseDecodeType[] | 디코드 유형입니다. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, BaseDecodeType) {#constructor_2}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, BaseDecodeType type)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| type | BaseDecodeType | 디코드 유형. |

## 예제

이 샘플은 밝기 프레임에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame, params BaseDecodeType[]) {#constructor_3}

[`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame, params BaseDecodeType[] decodeTypes)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |
| decodeTypes | BaseDecodeType[] | 디코드 유형입니다. |

## 예제

이 샘플은 밝기 프레임에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## BarCodeReader(LuminanceFrame) {#constructor_1}

밝기 프레임에서 [`BarCodeReader`](../) 클래스를 새 인스턴스로 초기화합니다.

```csharp
public BarCodeReader(LuminanceFrame frame)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 읽기 위한 밝기 프레임. |

## 예제

이 샘플은 밝기 프레임에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


