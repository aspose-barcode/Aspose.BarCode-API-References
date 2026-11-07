---
title: "method"
linktitle: "Decode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Декодирует поле Customer Information из символьной схемы AustraliaPost. Может использоваться для различной интерпретации данных из кодировок NTable и CTable. Данные предоставляются в виде ряда значений полос: 0, 1, 2 или 3 в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Декодировать поле Customer Information из символьной системы AustraliaPost. Может использоваться для различной интерпретации данных из кодировок NTable и CTable. Данные предоставляются в виде строки значений штрихов: 0, 1, 2 или 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Type | Описание |
| --- | --- | --- |
| customerInformationField | System::String | Поле Customer Information, закодированное в виде ряда необработанных значений полос: 0, 1, 2 или 3 |

### ReturnValue

строка декодированного поля Customer Information
## Примечания



Этот пример показывает, как декодировать данные с помощью интерфейса [AustraliaPostCustomerInformationDecoder](../)
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

## См. также

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
