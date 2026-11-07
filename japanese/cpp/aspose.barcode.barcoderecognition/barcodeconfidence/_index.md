---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "列挙型です。C++ での認識信頼度レベルを含みます。"
type: docs
weight: 3500
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


認識の信頼度レベルを含みます。

```cpp
enum class BarCodeConfidence : int32_t
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) は、コードテキストが正しく認識されなかった、またはバーコードが可能性のある偽造として検出された場合の信頼度です。 |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) は、チェックサムが弱い、またはなしのバーコード（主に 1D バーコード）の信頼度です。コードテキストに誤認識や偽の認識が含まれる可能性があります。 |

は低い |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) は、Reed–Solomon のような BCH コードで確認された信頼度です。読み取られたコードテキストにエラーや偽の認識があってはなりません。 |

## 備考


このサンプルは、バーコードの種類に応じて BarCodeConfidence がどのように変化するかを示しています。
```cpp
[C#]
//中程度の信頼度
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//高い信頼度
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
