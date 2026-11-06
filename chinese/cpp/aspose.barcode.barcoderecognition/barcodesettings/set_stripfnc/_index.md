---
title: "method"
linktitle: "set_StripFNC"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。剥离 codetext 中的 FNC1、FNC2、FNC3 字符。默认值在 C++ 中为 false。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_stripfnc/
---
## BarcodeSettings::set_StripFNC method


从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_StripFNC(bool value)
```

## 备注


此示例展示了如何剥离 FNC 字符
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC 已禁用
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC 已启用
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC disabled
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC enabled
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。
## 另见

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
