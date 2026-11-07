---
title: "μέθοδος"
linktitle: "Decode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Αποκωδικοποιεί το Πεδίο Πληροφοριών Πελάτη από τη συμβολική AustraliaPost. Μπορεί να χρησιμοποιηθεί για διαφορετική ερμηνεία δεδομένων από την κωδικοποίηση NTable και CTable. Τα δεδομένα παρέχονται ως σειρά τιμών μπαρ: 0, 1, 2 ή 3 σε C++."
type: docs
weight: 100
url: /el/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Αποκωδικοποίηση του πεδίου Customer Information από τη συμβολή AustraliaPost. Μπορεί να χρησιμοποιηθεί για διαφορετική κωδικοποίηση **NTable** και **CTable**. Τα δεδομένα παρέχονται ως σειρά τιμών γραμμής: 0, 1, 2 ή 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| customerInformationField | System::String | Το Πεδίο Πληροφοριών Πελάτη κωδικοποιείται ως σειρά ακατέργαστων τιμών μπαρ: 0, 1, 2 ή 3 |

### ReturnValue

η αποκωδικοποιημένη συμβολοσειρά του Πεδίου Πληροφοριών Πελάτη
## Σχόλια



Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε δεδομένα με το interface [AustraliaPostCustomerInformationDecoder](../)
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

## Δείτε επίσης

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
