---
title: "method"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene il testo del codice con codifica in C++."
type: docs
weight: 1000
url: /it/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Ottiene il testo del codice con codifica.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| codifica | System::SharedPtr\<System::Text::Encoding\> | La codifica per il testo del codice. |

### ReturnValue

Una stringa contenente il testo del codice riconosciuto.
## Osservazioni



Questo esempio mostra come utilizzare **GetCodeText**:


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Vedi anche

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
