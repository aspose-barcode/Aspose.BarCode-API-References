---
title: "metot"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. AustraliaPost sembolojisinden Müşteri Bilgi Alanını çözer. NTable ve CTable kodlamasından farklı veri yorumlamaları için kullanılabilir. Veri, C++ içinde 0, 1, 2 veya 3 değerlerinden oluşan bir çubuk değeri satırı olarak sağlanır."
type: docs
weight: 100
url: /tr/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


AustraliaPost sembolojisinden Müşteri Bilgi Alanını çöz. NTable ve CTable kodlamasından farklı veri yorumlamaları için kullanılabilir. Veri, 0, 1, 2 veya 3 değerlerine sahip bir çubuk değerleri satırı olarak sağlanır.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| customerInformationField | System::String | Müşteri Bilgi Alanı, ham çubuk değerleri satırı olarak kodlanmıştır: 0, 1, 2 veya 3 |

### ReturnValue

çözülen Müşteri Bilgi Alanı dizesi
## Açıklamalar



Bu örnek, [AustraliaPostCustomerInformationDecoder](../) arayüzüyle verinin nasıl çözüleceğini gösterir
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

## Ayrıca Bakınız

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
