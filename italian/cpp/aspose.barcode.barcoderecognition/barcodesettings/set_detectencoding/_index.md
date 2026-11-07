---
title: "method"
linktitle: "set_DetectEncoding"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode. Il valore predefinito è true in C++."
type: docs
weight: 800
url: /it/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_detectencoding/
---
## BarcodeSettings::set_DetectEncoding method


Il flag che forza il motore a rilevare la codifica del testo del codice per i set di caratteri Unicode. Il valore predefinito è true.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_DetectEncoding(bool value)
```

## Osservazioni


Questo esempio mostra come rilevare la codifica del testo al volo se DetectEncoding è abilitato
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //rilevamento della codifica per set di caratteri Unicode è abilitato
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //rilevamento della codifica è disabilitato
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```


Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode
## Vedi anche

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
