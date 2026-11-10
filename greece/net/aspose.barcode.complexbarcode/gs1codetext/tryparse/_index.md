---
title: "GS1Codetext.TryParse"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "GS1Codetext μέθοδος. Προσπαθεί να αναλύσει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 σε μορφή AIvalueAIvalue και επιστρέφει δομημένα σφάλματα επικύρωσης. Ένα κυριολεκτικό  μέσα σε τιμή πρέπει να γραφτεί ως  δεν υποστηρίζεται άλλη ακολουθία διαφυγής και  δεν απαιτεί διαφυγή."
type: docs
weight: 140
url: /el/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Προσπαθεί να αναλύσει μια συμβολοσειρά στοιχείου GS1 σε αγκύλες με τη μορφή (AI)value(AI)value και επιστρέφει δομημένα σφάλματα επικύρωσης. Μια κυριολεκτική '(' μέσα σε μια τιμή πρέπει να γραφτεί ως \(; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | String | Αγκυλωμένη συμβολοσειρά στοιχείου GS1 για ανάλυση. |
| αποτέλεσμα | GS1Codetext& | Όταν αυτή η μέθοδος επιστρέφει true, περιέχει το αναλυμένο κείμενο GS1· διαφορετικά null. |
| validationResult | GS1ValidationResult& | Περιέχει το αποτέλεσμα επικύρωσης, ή null όταν *value* είναι null. |

### Τιμή Επιστροφής

True όταν η ανάλυση είναι επιτυχής· διαφορετικά false.

### Δείτε επίσης

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


