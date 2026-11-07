---
title: "メソッド"
linktitle: "ReadBarCodes"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で画像から BarCodeResults を読み取ります。"
type: docs
weight: 1300
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader::ReadBarCodes method


画像から [BarCodeResult](../../barcoderesult/) を読み取ります。

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::ReadBarCodes()
```


### ReturnValue

画像上で認識された [BarCodeResult](../../barcoderesult/) の配列を返します。何も認識されなかった場合、空の配列が返されます。
## 備考


このサンプルは、[BarCodeReader](../) を使用してバーコードを読み取る方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


## 関連項目

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
