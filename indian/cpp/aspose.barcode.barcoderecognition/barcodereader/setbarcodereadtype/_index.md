---
title: "विधि"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. पहचान के लिए SingleDecodeType प्रकार की एरे सेट करता है। इसे C++ में ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए।"
type: docs
weight: 1600
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


पहचान के लिए [SingleDecodeType](../../singledecodetype/) प्रकार की एरे सेट करता है। इसे [ReadBarCodes()](../readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | पढ़ने के लिए [SingleDecodeType](../../singledecodetype/) प्रकार की एरे। |
## टिप्पणियाँ



यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
