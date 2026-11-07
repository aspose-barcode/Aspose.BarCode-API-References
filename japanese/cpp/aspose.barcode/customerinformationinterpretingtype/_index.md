---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. AustralianPost バーコードの顧客情報の解釈タイプ (CTable、NTable、または Other) を C++ で定義します。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


AustralianPost の [BarCode](../) の顧客情報の解釈タイプ (CTable、NTable、または Other) を定義します。

```cpp
enum class CustomerInformationInterpretingType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| CTable | 0 | CTable を使用して顧客情報を解釈します。A..Z、a..z、1..9、スペース、# 記号が使用可能です。 |
| NTable | 1 | NTable を使用して顧客情報を解釈します。数字が使用可能です。 |
| Other | 2 | 顧客情報を解釈しません。0、1、2、または 3 記号のみが使用可能です。 |

## 備考


これらのサンプルは Australia Post バーコードの生成と認識方法を示しています
```cpp
    [C#]
//このサンプルは CTable 解釈タイプを使用した Australia Post バーコードの生成と認識方法を示しています
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
//このサンプルは、Customer Interpreting Type を使用せずに Australia Post バーコードを生成および認識する方法を示します。
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

## 関連項目

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
