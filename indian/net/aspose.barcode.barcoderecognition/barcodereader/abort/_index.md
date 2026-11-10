---
title: "BarCodeReader.Abort"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader मेथड। यह फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड नहीं है और कॉल करने के तुरंत बाद नियंत्रण वापस करता है। इस मेथड का उपयोग तब किया जाना चाहिए जब पहचान प्रक्रिया बहुत लंबी हो।"
type: docs
weight: 90
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/abort/
---
## BarCodeReader.Abort method

फ़ंक्शन अन्य थ्रेड से वर्तमान मान्यता सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड है और कॉल करने के तुरंत बाद नियंत्रण लौटाता है। जब मान्यता प्रक्रिया बहुत लंबी हो तो इस मेथड का उपयोग किया जाना चाहिए।

```csharp
public void Abort()
```

## उदाहरण

यह उदाहरण दिखाता है कि अन्य थ्रेड से Abort फ़ंक्शन को कैसे कॉल करें।

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

### और देखें

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


