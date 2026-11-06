---
title: "طريقة"
linktitle: "Decode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. فكّ حقل معلومات العميل من رموز AustraliaPost. يمكن استخدامها لتفسير بيانات مختلفة من ترميز NTable و CTable. تُقدَّم البيانات كسطر من قيم الأشرطة: 0، 1، 2 أو 3 في C++."
type: docs
weight: 100
url: /ar/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


فك حقل معلومات العميل من ترميز AustraliaPost. يمكن استخدامه لتفسير بيانات مختلفة من ترميز NTable و CTable. تُقدم البيانات كسطر من قيم الأعمدة: 0، 1، 2 أو 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| customerInformationField | System::String | حقل معلومات العميل المشفر كسطر من قيم الأشرطة الخام: 0، 1، 2 أو 3 |

### ReturnValue

سلسلة حقل معلومات العميل المفككة
## ملاحظات



يعرض هذا المثال كيفية فكّ البيانات باستخدام واجهة [AustraliaPostCustomerInformationDecoder](../)
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

## انظر أيضًا

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
