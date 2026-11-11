---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "AustraliaPostCustomerInformationDecoder methode. Decode Customer Information Field van de AustraliaPost-symbool. Kan worden gebruikt voor verschillende gegevensinterpretaties van NTable- en CTable-codering. Gegevens worden geleverd als een rij balkwaarden 0 1 2 of 3"
type: docs
weight: 10
url: /nl/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

Decodeer het Klantinformatieveld uit de AustraliaPost-symbologie. Kan worden gebruikt voor verschillende gegevensinterpretaties van NTable- en CTable-codering. Gegevens worden geleverd als een rij van balkwaarden: 0, 1, 2 of 3.

```csharp
public string Decode(string customerInformationField)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| customerInformationField | String | Het Customer Information Field gecodeerd als een rij ruwe balkwaarden: 0, 1, 2 of 3 |

### Retourwaarde

de gedecodeerde Customer Information Field-tekenreeks

## Voorbeelden

Deze voorbeeld toont hoe gegevens te decoderen met de AustraliaPostCustomerInformationDecoder-interface

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

### Zie ook

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


