---
title: "method"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Decodifica il Customer Information Field dalla simbologia AustraliaPost. Può essere usato per diverse interpretazioni dei dati dalla codifica NTable e CTable. I dati sono forniti come una riga di valori di barra: 0, 1, 2 o 3 in C++."
type: docs
weight: 100
url: /it/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Decodifica il campo Customer Information dalla simbologia AustraliaPost. Può essere utilizzato per diverse interpretazioni dei dati dalla codifica NTable e CTable. I dati sono forniti come una riga di valori di barra: 0, 1, 2 o 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| customerInformationField | System::String | Il Customer Information Field codificato come una riga di valori di barra grezzi: 0, 1, 2 o 3 |

### ReturnValue

la stringa del Customer Information Field decodificata
## Osservazioni



Questo esempio mostra come decodificare i dati con l'interfaccia [AustraliaPostCustomerInformationDecoder](../)
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

## Vedi anche

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
