---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeSettings 属性。仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条码将被过滤掉。默认值为 false"
type: docs
weight: 50
url: /zh/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

仅返回明确指定用于识别的条形码类型。启用后，其他兼容或等效类型的已识别条形码将被过滤掉。默认值为 false。

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

仅返回明确指定用于识别的条形码类型。默认值为 false。

## 示例

此示例展示如何仅将识别结果限制为请求的条形码类型

```csharp
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
//识别兼容类型：EAN13、UPCA、ISSN、ISMN、ISBN（EAN13 将作为等价的 UPCA 返回）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### 另见

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


