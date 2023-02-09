---
title: Timeout
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: मलसेकंड में पहचन प्रक्रय क टइमआउट प्रप्त य सेट करत है
type: docs
weight: 70
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

मिलीसेकंड में पहचान प्रक्रिया का टाइमआउट प्राप्त या सेट करता है।

```csharp
public int Timeout { get; set; }
```

### संपत्ति मूल्य

टाइमआउट.

### उदाहरण

यह नमूना दिखाता है कि बड़ी छवियों पर टाइमकाउंट के साथ हैंग होने की पहचान से कैसे बचा जाए

```csharp
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

### यह सभी देखें

* class [BarCodeReader](../)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* सभा [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->