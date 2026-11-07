---
title: "methode"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Decode Customer Information Field van AustraliaPost-symbologie. Kan worden gebruikt voor verschillende gegevensinterpretaties van NTable- en CTable-codering. Gegevens worden geleverd als een rij balkwaarden: 0, 1, 2 of 3 in C++."
type: docs
weight: 100
url: /nl/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Decode Customer Information Field van de AustraliaPost-symbologie. Kan worden gebruikt voor verschillende gegevensinterpretaties van NTable- en CTable-codering. Gegevens worden geleverd als een rij balkwaarden: 0, 1, 2 of 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| customerInformationField | System::String | Het Customer Information Field gecodeerd als een rij ruwe balkwaarden: 0, 1, 2 of 3 |

### ReturnValue

de gedecodeerde Customer Information Field string
## Opmerkingen



Deze voorbeeld toont hoe gegevens te decoderen met de [AustraliaPostCustomerInformationDecoder](../) interface
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

## Zie ook

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
