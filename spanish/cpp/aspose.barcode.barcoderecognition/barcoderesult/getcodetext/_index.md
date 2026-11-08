---
title: "método"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene el texto del código con codificación en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Obtiene el texto del código con codificación.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codificación | System::SharedPtr\<System::Text::Encoding\> | La codificación para el texto del código. |

### ReturnValue

Una cadena que contiene el texto del código reconocido.
## Observaciones



Este ejemplo muestra cómo usar **GetCodeText**:


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

## Ver también

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
