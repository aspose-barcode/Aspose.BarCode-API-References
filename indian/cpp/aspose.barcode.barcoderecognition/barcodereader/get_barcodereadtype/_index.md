---
title: "विधि"
linktitle: "get_BarCodeReadType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है। C++ में ReadBarCodes को कॉल करने से पहले इसे सेट किया जाना चाहिए।"
type: docs
weight: 1000
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/get_barcodereadtype/
---
## BarCodeReader::get_BarCodeReadType method


पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है। इसे [ReadBarCodes](../readbarcodes/) को कॉल करने से पहले सेट किया जाना चाहिए।

```cpp
System::SharedPtr<BaseDecodeType> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_BarCodeReadType()
```

## टिप्पणियाँ


यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

## और देखें

* Class [BaseDecodeType](../../basedecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
