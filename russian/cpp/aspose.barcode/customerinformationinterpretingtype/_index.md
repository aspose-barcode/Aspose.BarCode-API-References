---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Определяет тип интерпретации (CTable, NTable или Other) клиентской информации для AustralianPost BarCode в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


Определяет тип интерпретации (CTable, NTable или Other) клиентской информации для AustralianPost [BarCode](../).

```cpp
enum class CustomerInformationInterpretingType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| CTTable | 0 | Используйте CTable для интерпретации клиентской информации. Разрешены A..Z, a..z, 1..9, пробел и символ #. |
| NTable | 1 | Используйте NTable для интерпретации клиентской информации. Разрешены цифры. |
| Other | 2 | Не интерпретировать клиентскую информацию. Разрешены только символы 0, 1, 2 или 3. |

## Примечания


Эти примеры показывают, как генерировать и распознавать штрих-код Australia Post
```cpp
    [C#]
//Этот пример показывает, как генерировать и распознавать штрих-код Australia Post с типом интерпретации CTable.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//Этот пример показывает, как генерировать и распознавать штрих-код Australia Post без типа интерпретации клиента.
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## См. также

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
