---
title: "メソッド"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++でコードテキストをバイト列として設定します。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


codetext をバイト列として設定します。

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | コードテキストのバイト |

## 関連項目

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeText | System::String | CodeText 文字列 |
| エンコーディング | System::SharedPtr\<System::Text::Encoding\> | 適用されたエンコーディング |
## 備考


Unicode の **codeText** を指定された **encoding** を使用してバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートしている場合、関数は自動的に [バイト順マーク (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) を挿入します。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみを対象としています。国別または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこのメソッドは古くなっていると見なされます。最新の使用例では、Unicode データには [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）、または HIBC バーコード（2D を含む）で使用すると、対応するバーコード規格でサポートされておらず、予測できない結果になる可能性があります。


この例は、さまざまなエンコーディングを使用して 2D バーコードの Unicode エンコードテキストを設定する方法として **SetCodeText** の使用方法を示しています：


```cpp
[C#]
//UTF-8（BOM 付き）で QR コードテキストをエンコード
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Shift-JIS（日本語エンコーディング）で DataMatrix テキストをエンコード
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## 関連項目

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codeText | System::String | CodeText 文字列 |
| エンコーディング | System::SharedPtr\<System::Text::Encoding\> | 適用されたエンコーディング |
| insertBOM | bool | 指定されたエンコーディングがサポートしている場合（例: UTF-8、UTF-16、UTF-32）にバイト順マーク（BOM）を挿入するかどうかを示します。**true** に設定すると BOM が追加され、**false** に設定すると、エンコーディングが通常 BOM を使用する場合でも BOM が省略されます。 |
## 備考


Unicode の **codeText** を指定された **encoding** を使用してバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングがサポートしており、**insertBOM** が **true** に設定されている場合、関数は [バイト順マーク (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) を含めます。

この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）のみを対象としています。国別または特殊なエンコーディングを使用して Unicode テキストを手動でエンコードできるようにしますが、現代のアプリケーションではこのメソッドは古くなっていると見なされます。最新の使用例では、Unicode データには [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) エンコーディングの使用が推奨されます。

この関数を 1D バーコード、GS1 準拠のバーコード（2D を含む）、または HIBC バーコード（2D を含む）で使用すると、対応するバーコード規格でサポートされておらず、予測できない結果になる可能性があります。


この例は、2D バーコードで BOM の有無にかかわらず **SetCodeText** を使用する方法を示しています。


```cpp
[C#]
    //UTF-8（BOM付き）でコードテキストをエンコードする
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //UTF-8（BOMなし）でコードテキストをエンコードする
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## 関連項目

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
