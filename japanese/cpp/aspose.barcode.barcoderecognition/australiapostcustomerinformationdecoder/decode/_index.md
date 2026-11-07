---
title: "メソッド"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. AustraliaPostシンボルからカスタマー情報フィールドをデコードします。NTableおよびCTableエンコーディングからの異なるデータ解釈に使用できます。データはC++で0、1、2、または3のバー値の列として提供されます。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


AustraliaPost シンボルからカスタマー情報フィールドをデコードします。NTable と CTable エンコーディングからのさまざまなデータ解釈に使用できます。データは 0、1、2、または 3 のバー値の行として提供されます。

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| customerInformationField | System::String | カスタマー情報フィールドは、生のバー値（0、1、2、または3）の列としてエンコードされます |

### ReturnValue

デコードされたカスタマー情報フィールド文字列
## 備考



このサンプルは、[AustraliaPostCustomerInformationDecoder](../) インターフェイスを使用してデータをデコードする方法を示しています
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

## 関連項目

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
