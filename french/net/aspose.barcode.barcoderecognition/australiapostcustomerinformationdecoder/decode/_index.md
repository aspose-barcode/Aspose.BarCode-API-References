---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode AustraliaPostCustomerInformationDecoder. Décode le champ d'information client à partir de la symbologie AustraliaPost. Peut être utilisé pour différentes interprétations de données à partir des encodages NTable et CTable. Les données sont fournies sous forme d'une ligne de valeurs de barres 0 1 2 ou 3"
type: docs
weight: 10
url: /fr/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

Décode le champ d'information client à partir de la symbologie AustraliaPost. Peut être utilisé pour différentes interprétations de données à partir du codage NTable et CTable. Les données sont fournies sous forme d'une rangée de valeurs de barres : 0, 1, 2 ou 3.

```csharp
public string Decode(string customerInformationField)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| customerInformationField | String | Le champ d'information client encodé sous forme d'une ligne de valeurs de barres brutes : 0, 1, 2 ou 3 |

### Valeur de retour

la chaîne du champ d'information client décodé

## Exemples

Cet exemple montre comment décoder des données avec l'interface AustraliaPostCustomerInformationDecoder

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

### Voir aussi

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


