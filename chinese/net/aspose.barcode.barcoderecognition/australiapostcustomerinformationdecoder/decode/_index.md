---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "AustraliaPostCustomerInformationDecoder 方法。解码来自 AustraliaPost 符号的客户信息字段。可用于对 NTable 和 CTable 编码的不同数据进行解释。数据以 0、1、2 或 3 的条形值行提供"
type: docs
weight: 10
url: /zh/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

从 AustraliaPost 符号解码客户信息字段。可用于对 NTable 和 CTable 编码的不同数据解释。数据以一行条码值提供：0、1、2 或 3。

```csharp
public string Decode(string customerInformationField)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| customerInformationField | 字符串 | 客户信息字段以原始条形值行编码：0、1、2 或 3 |

### 返回值

已解码的客户信息字段字符串

## 示例

此示例展示了如何使用 AustraliaPostCustomerInformationDecoder 接口解码数据

```csharp
[C#]
string[] N_Table = { "00", "01", "02", "10", "11", "12", "20", "21", "22", "30" };
public string Decode(string customerInformationField)
{
    StringBuilder bd = new StringBuilder();
    for (int i = 0; customerInformationField.Length > i; i += 2)
    {
        if (customerInformationField.Length >= i + 2)
        {
            string tmp = customerInformationField.Substring(i, 2);
            for (int j = 0; N_Table.Length > j; j++)
            {
                if (N_Table[j].Equals(tmp))
                {
                    bd.Append(j);
                    break;
                }
            }
        }
    }
     return bd.ToString();
}
```

### 另见

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


