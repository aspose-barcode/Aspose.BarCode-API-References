---
title: "BarCodeReader.Abort"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 메서드. 현재 인식 세션을 다른 스레드에서 종료하도록 요청하는 함수. Abort은 차단할 수 없는 메서드이며 호출 직후 제어를 반환한다. 인식 과정이 너무 오래 걸릴 때 이 메서드를 사용해야 한다."
type: docs
weight: 90
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

이 함수는 다른 스레드에서 현재 인식 세션의 종료를 요청합니다. Abort은 차단할 수 없는 메서드이며 호출 직후 제어를 반환합니다. 인식 프로세스가 너무 오래 걸릴 때 이 메서드를 사용해야 합니다.

```csharp
public void Abort()
```

## 예제

이 샘플은 다른 스레드에서 Abort 함수를 호출하는 방법을 보여준다.

```csharp
[C#]
private static void ThreadRecognize(object readerObj)
{
    BarCodeReader reader = (BarCodeReader)readerObj;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeType);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}

BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128);
Thread thread1 = new Thread(ThreadRecognize);
thread1.Start(reader);
Thread.Sleep(100);
reader.Abort();
[VB.NET]
Private Shared Sub ThreadRecognize(readerObj As Object)
    Dim reader As BarCodeReader = readerObj
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Sub

Dim reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
Dim thread1 As New Thread(AddressOf ThreadRecognize)
thread1.Start(reader)
Thread.Sleep(100)
reader.Abort()
```

### 또 보기

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


