---
title: "BarCodeReader.SetBarCodeImage"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 메서드. 인식을 위한 비트맵 이미지를 설정합니다. ReadBarCodes 메서드 호출 전에 호출해야 합니다."
type: docs
weight: 120
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/
---
## SetBarCodeImage(Bitmap) {#setbarcodeimage_3}

인식을 위한 비트맵 이미지를 설정합니다. ReadBarCodes() 메서드 호출 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(Bitmap value)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | Bitmap | 인식을 위한 비트맵 이미지입니다. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle[]) {#setbarcodeimage_5}

인식을 위한 비트맵 이미지와 여러 영역을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle[] areas)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | Bitmap | 인식을 위한 비트맵 이미지입니다. |
| areas | Rectangle[] | 인식을 위한 영역 목록 |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(Bitmap, Rectangle) {#setbarcodeimage_4}

인식을 위한 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(Bitmap value, Rectangle area)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | Bitmap | 인식을 위한 비트맵 이미지입니다. |
| area | Rectangle | 인식을 위한 영역 |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(string) {#setbarcodeimage_7}

인식을 위한 이미지 파일을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(string filename)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | 인식을 위한 이미지 파일입니다. |

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

## SetBarCodeImage(Stream) {#setbarcodeimage_6}

인식을 위한 이미지 스트림을 설정합니다. ReadBarCodes() 메서드를 호출하기 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 인식을 위한 이미지 스트림입니다. |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle) {#setbarcodeimage_1}

인식을 위해 밝기 프레임과 영역을 설정합니다. [`ReadBarCodes`](../readbarcodes/) 메서드 호출 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle area)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 인식을 위한 밝기 프레임입니다. |
| area | Rectangle | 인식 영역. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame, Rectangle[]) {#setbarcodeimage_2}

인식을 위해 밝기 프레임과 여러 영역을 설정합니다. [`ReadBarCodes`](../readbarcodes/) 메서드 호출 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(LuminanceFrame frame, Rectangle[] areas)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 인식을 위한 밝기 프레임입니다. |
| areas | Rectangle[] | 인식 영역 배열입니다. |

## 예제

이 샘플은 밝기 프레임의 지정된 영역에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## SetBarCodeImage(LuminanceFrame) {#setbarcodeimage}

인식을 위해 밝기 프레임을 설정합니다. [`ReadBarCodes`](../readbarcodes/) 메서드 호출 전에 호출해야 합니다.

```csharp
public void SetBarCodeImage(LuminanceFrame frame)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프레임 | LuminanceFrame | 인식을 위한 밝기 프레임입니다. |

## 예제

이 샘플은 밝기 프레임에서 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* class [LuminanceFrame](../../luminanceframe/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


