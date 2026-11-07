---
title: "विधि"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में पहचाने गए BarCodeResults की सरणी प्राप्त करता है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


पहचाने गए [BarCodeResult](../../barcoderesult/)s की सरणी प्राप्त करता है

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## टिप्पणियाँ


पहचाने गए [BarCodeResult](../../barcoderesult/)s की सरणी

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

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
