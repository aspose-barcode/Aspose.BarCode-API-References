---
title: "विधि"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में C++ में सेट करता है।"
type: docs
weight: 400
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में सेट करता है।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## टिप्पणियाँ


टाइमआउट।

यह उदाहरण दिखाता है कि बड़े चित्रों पर टाइमआउट के साथ पहचान हंग को कैसे रोकें।
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

## और देखें

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
