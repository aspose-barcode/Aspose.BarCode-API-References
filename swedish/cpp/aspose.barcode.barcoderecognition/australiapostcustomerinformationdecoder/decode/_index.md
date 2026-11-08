---
title: "metod"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Avkoda Customer Information Field från AustraliaPost-symbologi. Kan användas för olika datainterpretationer från NTable- och CTable-kodning. Data tillhandahålls som en rad av stapelvärden: 0, 1, 2 eller 3 i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Avkoda Customer Information Field från AustraliaPost-symbologi. Kan användas för olika datainterpretationer från NTable- och CTable-kodning. Data tillhandahålls som en rad av stapelvärden: 0, 1, 2 eller 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| customerInformationField | System::String | Customer Information Field kodad som rad av råa stapelvärden: 0, 1, 2 eller 3 |

### ReturnValue

den avkodade Customer Information Field-strängen
## Anmärkningar



Detta exempel visar hur man avkodar data med gränssnittet [AustraliaPostCustomerInformationDecoder](../).
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

## Se även

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
