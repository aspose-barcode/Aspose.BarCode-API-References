---
title: "method"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле клиентской информации при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодирования, и последовательность \\\"333\\\" шаблонов заполняется как буква \\\"z\\\" в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле Customer Information при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодов, и последовательность "333" шаблонов заполнения декодируется как буква "z".

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## Примечания


Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения при декодировании методом CTable

Этот пример показывает, как генерировать и распознавать штрих‑код Australia Post с типом интерпретации CTable и игнорированием шаблонов заполнения.
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## См. также

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
