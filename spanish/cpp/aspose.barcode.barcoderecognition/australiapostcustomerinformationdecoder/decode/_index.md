---
title: "método"
linktitle: "Decode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Decodifica el Customer Information Field de la simbología AustraliaPost. Puede usarse para diferentes interpretaciones de datos de la codificación NTable y CTable. Los datos se proporcionan como una fila de valores de barra: 0, 1, 2 o 3 en C++."
type: docs
weight: 100
url: /es/cpp/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder::Decode method


Decodifica el campo de información del cliente de la simbología AustraliaPost. Puede usarse para diferentes interpretaciones de datos a partir de la codificación NTable y CTable. Los datos se proporcionan como una fila de valores de barra: 0, 1, 2 o 3.

```cpp
virtual System::String Aspose::BarCode::BarCodeRecognition::AustraliaPostCustomerInformationDecoder::Decode(System::String customerInformationField)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| customerInformationField | System::String | El Customer Information Field codificado como una fila de valores de barra sin procesar: 0, 1, 2 o 3 |

### ReturnValue

la cadena del Customer Information Field decodificado
## Observaciones



Este ejemplo muestra cómo decodificar datos con la interfaz [AustraliaPostCustomerInformationDecoder](../)
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

## Ver también

* Class [AustraliaPostCustomerInformationDecoder](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
