---
title: "BaseDecodeType.TryParse"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Μέθοδος BaseDecodeType. Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην αντίστοιχη του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε"
type: docs
weight: 40
url: /el/net/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## TryParse(string, out SingleDecodeType) {#tryparse_2}

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool TryParse(string parsingType, out SingleDecodeType result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | String | Μια συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή "EAN8" ή "EAN13" ή "CodaBar"... για μετατροπή. |
| αποτέλεσμα | SingleDecodeType& | Επιστρέφεται ένα πραγματικό SingleDecodeType όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: DecodeType.None. |

### Τιμή Επιστροφής

**true** if parsingType was converted successfully; otherwise, **false**.

### Δείτε επίσης

* class [SingleDecodeType](../../singledecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out MultiDecodeType) {#tryparse_1}

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool TryParse(string parsingType, out MultiDecodeType result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |
| αποτέλεσμα | MultiDecodeType& | Επιστρέφεται ένα πραγματικό MultiDecodeType όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: new MultiDecodeType(DecodeType.None) |

### Τιμή Επιστροφής

**true** if parsingType was converted successfully; otherwise, **false**.

### Δείτε επίσης

* class [MultiDecodeType](../../multidecodetype/)
* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## TryParse(string, out BaseDecodeType) {#tryparse}

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool TryParse(string parsingType, out BaseDecodeType result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |
| αποτέλεσμα | BaseDecodeType& | Επιστρέφεται ένα πραγματικό MultiDecodeType όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: DecodeType.None. |

### Τιμή Επιστροφής

**true** if parsingType was converted successfully; otherwise, **false**.

### Δείτε επίσης

* class [BaseDecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


