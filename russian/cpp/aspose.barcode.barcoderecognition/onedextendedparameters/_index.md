---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters класс"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters класс. Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный кодовый текст и контрольная сумма в C++."
type: docs
weight: 2700
url: /ru/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный кодтекст и контрольная сумма

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Описание |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | Получает контрольную сумму для 1D штрихкодов. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** проверяет, имеют ли все параметры только значения по умолчанию |
| [get_Value](./get_value/)() const | Получает кодовый текст 1D штрихкодов без контрольной суммы. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [OneDExtendedParameters](./). |
## Примечания


Этот пример показывает, как получить значение 1D штрихкода и контрольную сумму.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## См. также

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
