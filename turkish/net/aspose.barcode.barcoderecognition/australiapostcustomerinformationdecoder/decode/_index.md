---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "AustraliaPostCustomerInformationDecoder yöntemi. AustraliaPost sembolojisinden Müşteri Bilgi Alanını çözer. NTable ve CTable kodlamasından farklı veri yorumlamaları için kullanılabilir. Veri, 0 1 2 veya 3 bar değerlerinden oluşan bir satır olarak sağlanır"
type: docs
weight: 10
url: /tr/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

AustraliaPost sembolojisinden Müşteri Bilgi Alanını çözer. NTable ve CTable kodlamasından farklı veri yorumlamaları için kullanılabilir. Veri, 0, 1, 2 veya 3 değerlerine sahip çubuk değerleri satırı olarak sağlanır.

```csharp
public string Decode(string customerInformationField)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| customerInformationField | Dize | Müşteri Bilgi Alanı, ham bar değerleri satırı olarak kodlanmıştır: 0, 1, 2 veya 3 |

### Dönüş Değeri

çözülen Müşteri Bilgi Alanı dizesi

## Örnekler

Bu örnek, AustraliaPostCustomerInformationDecoder arayüzüyle verinin nasıl çözüleceğini gösterir

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

### Ayrıca Bakınız

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


