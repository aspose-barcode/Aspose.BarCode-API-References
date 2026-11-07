---
title: "μέθοδος"
linktitle: "TryParse"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "μέθοδος. Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../../singledecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | System::String | Μια συμβολοσειρά που περιέχει ένα [SingleDecodeType](../../singledecodetype/) στη μορφή "EAN8" ή "EAN13" ή "CodaBar"... για μετατροπή. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Επιστρέφεται ένα πραγματικό [SingleDecodeType](../../singledecodetype/), όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Δείτε επίσης

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [MultiDecodeType](../../multidecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | System::String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση [MultiDecodeType](../../multidecodetype/) για μετατροπή. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Επιστρέφεται ένα πραγματικό [MultiDecodeType](../../multidecodetype/), όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Δείτε επίσης

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [BaseDecodeType](../) στην παρουσία του, αφού προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | System::String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση [MultiDecodeType](../../multidecodetype/) για μετατροπή. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Επιστρέφεται ένα πραγματικό [MultiDecodeType](../../multidecodetype/), όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Δείτε επίσης

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
