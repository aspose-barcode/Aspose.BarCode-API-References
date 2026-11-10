---
title: "DecodeType.TryParse"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "DecodeType μέθοδος. Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Η τιμή επιστροφής υποδεικνύει αν η μετατροπή πέτυχε ή απέτυχε."
type: docs
weight: 980
url: /el/net/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_1}

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | String | Μια συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή "EAN8" ή "EAN13" ή "CodaBar"... για μετατροπή. |
| αποτέλεσμα | SingleDecodeType& | Ένα πραγματικό SingleDecodeType επιστρέφει, όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: DecodeType.None. |

### Τιμή Επιστροφής

**true** if parsingType was converted successfully; otherwise, **false**.

### Δείτε επίσης

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse}

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | String | Μια συμβολοσειρά στη μορφή είτε "AllSupportedTypes" είτε "EAN8,EAN13,CodaBar" για μετατροπή. |
| αποτέλεσμα | MultiDecodeType& | Επιστρέφεται ένα πραγματικό MultiDecodeType όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: new MultiDecodeType(DecodeType.None) |

### Τιμή Επιστροφής

**true** if parsingType was converted successfully; otherwise, **false**.

### Δείτε επίσης

* class [MultiDecodeType](../../multidecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


