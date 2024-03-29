---
title: StripFNC
second_title: Aspose.BarCode για Αναφορά API .NET
description: Αφαιρέστε τους χαρακτήρες FNC1 FNC2 FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 40
url: /el/net/aspose.barcode.barcoderecognition/barcodesettings/stripfnc/
---
## BarcodeSettings.StripFNC property

Αφαιρέστε τους χαρακτήρες FNC1, FNC2, FNC3 από το κείμενο κώδικα. Η προεπιλεγμένη τιμή είναι false.

```csharp
public bool StripFNC { get; set; }
```

### Αξία περιουσίας

Αφαιρέστε τους χαρακτήρες FNC1, FNC2, FNC3 από το κωδικοποιημένο κείμενο. Η προεπιλεγμένη τιμή είναι ψευδής.

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να αφαιρέσετε τους χαρακτήρες FNC

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC απενεργοποιημένο
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC ενεργοποιημένο
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'Το StripFNC απενεργοποιήθηκε
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC ενεργοποιημένο
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Δείτε επίσης

* class [BarcodeSettings](../)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../barcodesettings/)
* συνέλευση [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
