---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Представляет регион распознанного штрихкода и угол штрихкода в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Представляет регион распознанного штрих‑кода и угол штрих‑кода

```cpp
class BarCodeRegionParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Angle](./get_angle/)() const | Получает угол штрихкода (0-360). |
| [get_Points](./get_points/)() const | Получает массив [Point](../), ограничивающий регион штрихкода |
| [get_Quadrangle](./get_quadrangle/)() const | Получает [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/), ограничивающий регион штрихкода |
| [get_Rectangle](./get_rectangle/)() const | Получает **System::Drawing::Rectangle**, ограничивающий регион штрихкода |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [BarCodeRegionParameters](./). |
## Примечания


Этот пример показывает, как получить угол штрихкода и значения ограничивающего квадранта
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
