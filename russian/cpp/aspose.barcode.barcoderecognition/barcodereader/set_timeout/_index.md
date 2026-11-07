---
title: "method"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает тайм‑аут процесса распознавания в миллисекундах в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


Устанавливает тайм-аут процесса распознавания в миллисекундах.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
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
