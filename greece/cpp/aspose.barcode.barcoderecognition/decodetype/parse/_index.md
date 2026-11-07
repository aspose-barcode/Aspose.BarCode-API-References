---
title: "μέθοδος"
linktitle: "Parse"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "μέθοδος. Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../../singledecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | System::String | Μια συμβολοσειρά που περιέχει ένα [SingleDecodeType](../../singledecodetype/) στη μορφή "EAN8" ή "EAN13" ή "CodaBar"... για μετατροπή. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Ένα πραγματικό [SingleDecodeType](../../singledecodetype/) επιστρέφει, όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Δείτε επίσης

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
