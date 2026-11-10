---
title: "GS1DigitalLink.TryParse"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "GS1DigitalLink μέθοδος. Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης"
type: docs
weight: 190
url: /el/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | String | GS1 Digital Link URI προς ανάλυση. |
| αποτέλεσμα | GS1DigitalLink& | Όταν αυτή η μέθοδος επιστρέφει true, περιέχει το αναλυμένο GS1 Digital Link· διαφορετικά null. |
| validationResult | GS1ValidationResult& | Περιέχει το αποτέλεσμα επικύρωσης, ή null όταν *value* είναι null. |

### Τιμή Επιστροφής

True όταν η ανάλυση είναι επιτυχής· διαφορετικά false.

### Δείτε επίσης

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


