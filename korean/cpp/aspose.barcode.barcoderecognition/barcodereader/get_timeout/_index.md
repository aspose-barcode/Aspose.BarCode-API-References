---
title: "메서드"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 인식 프로세스의 제한 시간을 밀리초 단위로 가져옵니다."
type: docs
weight: 300
url: /ko/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


인식 프로세스의 제한 시간을 밀리초 단위로 가져옵니다.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## 비고


제한 시간입니다.

이 샘플은 대형 이미지에서 시간 초과로 인한 인식 중단을 방지하는 방법을 보여줍니다.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## 또 보기

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
