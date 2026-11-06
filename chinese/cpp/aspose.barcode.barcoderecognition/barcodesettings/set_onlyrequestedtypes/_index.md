---
title: "method"
linktitle: "set_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条形码将被过滤。默认值在 C++ 中为 false。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_onlyrequestedtypes/
---
## BarcodeSettings::set_OnlyRequestedTypes method


仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条形码将被过滤掉。默认值为 false。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_OnlyRequestedTypes(bool value)
```

## 备注


此示例展示了如何仅将识别结果限制为请求的条形码类型
```cpp
[C#]
//生成 EAN13 条形码
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//仅识别 UPCA 条形码（无结果，因为源是 EAN13）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//识别兼容类型：EAN13、UPCA、ISSN、ISMN、ISBN（EAN13 将作为等效的 UPCA 返回）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


仅返回明确指定用于识别的条形码类型。默认值为 false。
## 另见

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
