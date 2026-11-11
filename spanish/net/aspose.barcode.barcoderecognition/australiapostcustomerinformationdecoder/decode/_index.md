---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Método AustraliaPostCustomerInformationDecoder. Decodifica el Campo de Información del Cliente de la simbología AustraliaPost. Puede usarse para diferentes interpretaciones de datos a partir de la codificación NTable y CTable. Los datos se proporcionan como una fila de valores de barra 0 1 2 o 3"
type: docs
weight: 10
url: /es/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

Decodifica el Campo de Información del Cliente de la simbología AustraliaPost. Puede usarse para diferentes interpretaciones de datos a partir de la codificación NTable y CTable. Los datos se proporcionan como una fila de valores de barra: 0, 1, 2 o 3.

```csharp
public string Decode(string customerInformationField)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| customerInformationField | Cadena | El Campo de Información del Cliente codificado como una fila de valores de barra sin procesar: 0, 1, 2 o 3 |

### Valor de retorno

la cadena del Campo de Información del Cliente decodificado

## Ejemplos

Este ejemplo muestra cómo decodificar datos con la interfaz AustraliaPostCustomerInformationDecoder

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

### Ver también

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


