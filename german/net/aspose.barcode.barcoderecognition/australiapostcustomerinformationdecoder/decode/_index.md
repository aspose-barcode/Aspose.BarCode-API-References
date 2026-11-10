---
title: "AustraliaPostCustomerInformationDecoder.Decode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "AustraliaPostCustomerInformationDecoder-Methode. Dekodiert das Customer Information Field aus der AustraliaPost‑Symbologie. Kann für unterschiedliche Dateninterpretationen aus NTable‑ und CTable‑Kodierung verwendet werden. Daten werden als Reihe von Balkenwerten 0 1 2 oder 3 bereitgestellt."
type: docs
weight: 10
url: /de/net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/decode/
---
## AustraliaPostCustomerInformationDecoder.Decode method

Dekodiert das Customer Information Field aus der AustraliaPost‑Symbologie. Kann für verschiedene Dateninterpretationen aus NTable‑ und CTable‑Kodierung verwendet werden. Daten werden als Reihe von Balkenwerten bereitgestellt: 0, 1, 2 oder 3.

```csharp
public string Decode(string customerInformationField)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| customerInformationField | String | Das Customer Information Field als Reihe von rohen Balkenwerten kodiert: 0, 1, 2 oder 3 |

### Rückgabewert

die dekodierte Customer Information Field Zeichenkette

## Beispiele

Dieses Beispiel zeigt, wie Daten mit dem Interface AustraliaPostCustomerInformationDecoder dekodiert werden

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

### Siehe auch

* interface [AustraliaPostCustomerInformationDecoder](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


