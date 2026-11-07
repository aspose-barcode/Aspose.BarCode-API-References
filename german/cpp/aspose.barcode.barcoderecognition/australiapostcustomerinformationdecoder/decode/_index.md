---
title: "Methode"
linktitle: "Decode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Dekodiert das Customer Information Field aus der AustraliaPost-Symbologie. Kann für verschiedene Dateninterpretationen aus NTable- und CTable-Codierung verwendet werden. Daten werden als Reihe von Balkenwerten bereitgestellt: 0, 1, 2 oder 3 in C++."
type: docs
weight: 100
url: /de/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Dekodiert das Customer Information Field aus der AustraliaPost‑Symbologie. Kann für verschiedene Dateninterpretationen aus der NTable- und CTable-Kodierung verwendet werden. Die Daten werden als Reihe von Balkenwerten bereitgestellt: 0, 1, 2 oder 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| customerInformationField | System::String | Das Customer Information Field kodiert als Reihe von rohen Balkenwerten: 0, 1, 2 oder 3 |

### ReturnValue

der dekodierte Customer Information Field-String
## Hinweise



Dieses Beispiel zeigt, wie man Daten mit der Schnittstelle [AustraliaPostCustomerInformationDecoder](../) dekodiert
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

## Siehe auch

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
