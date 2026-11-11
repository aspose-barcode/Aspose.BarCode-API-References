---
title: "GS1DigitalLink.Create"
second_title: "Aspose.BarCode för .NET API-referens"
description: "GS1DigitalLink metod. Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och välja den enda tillgängliga primärnyckeln"
type: docs
weight: 20
url: /sv/net/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## Create(string, GS1Codetext) {#create}

Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och välja den enda tillgängliga primärnyckeln.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriStem | String | Absolut HTTP- eller HTTPS-URI-prefix före primärnyckeln. |
| codetext | GS1Codetext | GS1-kodtext vars element kopieras. |

### Returvärde

En GS1 Digital Link som innehåller de kopierade elementen.

### Se även

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)

---

## Create(string, GS1Codetext, string) {#create_1}

Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och använda den angivna primärnyckeln.

```csharp
public static GS1DigitalLink Create(string uriStem, GS1Codetext codetext, 
    string primaryApplicationIdentifier)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriStem | String | Absolut HTTP- eller HTTPS-URI-prefix före primärnyckeln. |
| codetext | GS1Codetext | GS1-kodtext vars element kopieras. |
| primaryApplicationIdentifier | String | Primärnyckel AI. |

### Returvärde

En GS1 Digital Link som innehåller de kopierade elementen.

### Se även

* class [GS1Codetext](../../gs1codetext/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


