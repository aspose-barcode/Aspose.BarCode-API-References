---
title:  method
linktitle: Decode
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Decode Customer Information Field from AustraliaPost symbology. Can be used for different data interpretation from NTable and CTable encoding. Data is provided as a row of bar values: 0, 1, 2 or 3 in C++.'
type: docs
weight: 100
url: /cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Decode Customer Information Field from AustraliaPost symbology. Can be used for different data interpretation from NTable and CTable encoding. Data is provided as a row of bar values: 0, 1, 2 or 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| customerInformationField | System::String | The Customer Information Field encoded as row of raw bar values: 0, 1, 2 or 3 |

### ReturnValue

the decoded Customer Information Field string
## Remarks



This sample shows how to decode data with [AustraliaPostCustomerInformationDecoder](../) interface 
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

## See Also

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
