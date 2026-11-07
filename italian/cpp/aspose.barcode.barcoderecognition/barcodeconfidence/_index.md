---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Contiene il livello di fiducia del riconoscimento in C++."
type: docs
weight: 3500
url: /it/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Contiene il livello di fiducia del riconoscimento

```cpp
enum class BarCodeConfidence : int32_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | fiducia di [Recognition](../../aspose.barcode.barcoderecognition.recognition/) del codice a barre dove il testo del codice non è stato riconosciuto correttamente o il codice a barre è stato rilevato come possibile falso |
|  | Moderate | 80 | fiducia di [Recognition](../../aspose.barcode.barcoderecognition.recognition/) del codice a barre (principalmente codici a barre 1D) con checksum debole o anche senza di esso. Potrebbe contenere alcuni errori di riconoscimento nel testo del codice o addirittura falsi riconoscimenti se |

è basso |
| Strong | 100 | fiducia di [Recognition](../../aspose.barcode.barcoderecognition.recognition/) confermata con codici BCH come Reed–Solomon. Non devono esserci errori nel testo del codice letto o riconoscimenti falsi |

## Osservazioni


Questo esempio mostra come BarCodeConfidence cambia, a seconda del tipo di codice a barre
```cpp
[C#]
//Fiducia moderata
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//Fiducia forte
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
