---
title: "method"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。解码来自 AustraliaPost 符号的客户信息字段。可用于对 NTable 和 CTable 编码的不同数据解释。数据以一行条值提供：0、1、2 或 3（在 C++ 中）。"
type: docs
weight: 100
url: /zh/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


从 AustraliaPost 符号解码客户信息字段。可用于对 NTable 和 CTable 编码的不同数据进行解释。数据以条值行的形式提供：0、1、2 或 3。

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| customerInformationField | System::String | 客户信息字段以原始条值行编码：0、1、2 或 3 |

### ReturnValue

已解码的客户信息字段字符串
## 备注



此示例展示了如何使用 [AustraliaPostCustomerInformationDecoder](../) 接口解码数据
```cpp
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

## 另见

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
