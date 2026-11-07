---
title: "विधि"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। C++ में पहचाने गए बारकोड की गिनती प्राप्त करता है।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


पहचाने गए बारकोड्स की गिनती प्राप्त करता है

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## टिप्पणियाँ


पहचाने गए बारकोड की गिनती

यह उदाहरण दिखाता है कि [BarCodeReader](../) के साथ बारकोड कैसे पढ़ें।
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
