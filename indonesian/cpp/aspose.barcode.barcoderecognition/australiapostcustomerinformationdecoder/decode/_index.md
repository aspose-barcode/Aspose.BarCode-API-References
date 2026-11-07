---
title: "metode"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Mendekode Customer Information Field dari simbol AustraliaPost. Dapat digunakan untuk interpretasi data yang berbeda dari enkoding NTable dan CTable. Data disediakan sebagai baris nilai bar: 0, 1, 2, atau 3 dalam C++."
type: docs
weight: 100
url: /id/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Dekode Customer Information Field dari simbol AustraliaPost. Dapat digunakan untuk interpretasi data yang berbeda dari enkoding NTable dan CTable. Data disediakan sebagai baris nilai bar: 0, 1, 2 atau 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| customerInformationField | System::String | Customer Information Field yang dienkode sebagai baris nilai bar mentah: 0, 1, 2, atau 3 |

### ReturnValue

string Customer Information Field yang terdekode
## Catatan



Contoh ini menunjukkan cara mendekode data dengan antarmuka [AustraliaPostCustomerInformationDecoder](../)
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

## Lihat Juga

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
