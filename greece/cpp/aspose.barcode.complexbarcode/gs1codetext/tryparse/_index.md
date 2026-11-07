---
title: "μέθοδος"
linktitle: "TryParse"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Προσπαθεί να αναλύσει ένα κείμενο στοιχείου GS1 σε αγκύλες με τη μορφή (AI)value(AI)value και επιστρέφει δομημένα σφάλματα επικύρωσης. Ένα κυριολεκτικό ''('' μέσα σε μια τιμή πρέπει να γραφτεί ως (; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και '')'' δεν απαιτεί διαφυγή σε C++."
type: docs
weight: 1600
url: /el/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Προσπαθεί να αναλύσει μια αγκυλωμένη συμβολοσειρά στοιχείου GS1 στη μορφή (AI)value(AI)value και επιστρέφει δομημένα σφάλματα επικύρωσης. Ένα κυριολεκτικό '(' μέσα σε μια τιμή πρέπει να γραφτεί ως (; δεν υποστηρίζεται άλλη ακολουθία διαφυγής, και το ')' δεν απαιτεί διαφυγή.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | System::String | Κείμενο στοιχείου GS1 σε αγκύλες για ανάλυση. |
| result | System::SharedPtr\<GS1Codetext\>\& | Όταν αυτή η μέθοδος επιστρέφει true, περιέχει το αναλυμένο κείμενο κωδικού GS1· διαφορετικά null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Περιέχει το αποτέλεσμα επικύρωσης, ή null όταν το *value* είναι null. |

### ReturnValue

True όταν η ανάλυση είναι επιτυχής· διαφορετικά false.

## Δείτε επίσης

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
