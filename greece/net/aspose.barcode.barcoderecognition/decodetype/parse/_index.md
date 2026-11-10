---
title: "DecodeType.Parse"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "DecodeType μέθοδος. Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Η τιμή επιστροφής υποδεικνύει αν η μετατροπή πέτυχε ή απέτυχε."
type: docs
weight: 960
url: /el/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
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


