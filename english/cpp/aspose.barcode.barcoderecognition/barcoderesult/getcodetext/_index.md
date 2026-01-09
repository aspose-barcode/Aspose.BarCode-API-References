---
title:  method
linktitle: GetCodeText
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Gets the code text with encoding in C++.'
type: docs
weight: 900
url: /cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Gets the code text with encoding.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| encoding | System::SharedPtr\<System::Text::Encoding\> | The encoding for codetext. |

### ReturnValue

A string containing recognized code text.
## Remarks



This example shows how to use **GetCodeText**:


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

## See Also

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
