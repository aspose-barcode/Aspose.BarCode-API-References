---
title: "method"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Получает тайм-аут процесса распознавания в миллисекундах в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


Получает тайм-аут процесса распознавания в миллисекундах.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## Примечания


Тайм‑аут.

Этот пример показывает, как избежать зависаний распознавания из‑за тайм‑аута на больших изображениях
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

## См. также

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
