---
title: "μέθοδος"
linktitle: "TryParse"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης σε C++."
type: docs
weight: 2000
url: /el/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | System::String | GS1 Digital Link URI για ανάλυση. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Όταν αυτή η μέθοδος επιστρέφει true, περιέχει το αναλυμένο GS1 Digital Link· διαφορετικά null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Περιέχει το αποτέλεσμα επικύρωσης, ή null όταν το *value* είναι null. |

### ReturnValue

True όταν η ανάλυση είναι επιτυχής· διαφορετικά false.

## Δείτε επίσης

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
