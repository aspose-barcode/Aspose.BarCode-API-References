---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill κλάση"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill κλάση. Δεδομένα SwissQR bill σε C++."
type: docs
weight: 2700
url: /el/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


Δεδομένα τιμολογίου SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Δημιουργεί και ορίζει μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή της συμβολοσειράς το \"RF\" και το υπόλοιπο modulo 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Καθορίζει εάν το συγκεκριμένο τιμολόγιο είναι ίσο με το τρέχον τιμολόγιο. |
| [get_Account](./get_account/)() const | Αποκτά τον αριθμό λογαριασμού του πιστωτή. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Αποκτά ή ορίζει τα εναλλακτικά σχήματα πληρωμής. |
| [get_Amount](./get_amount/)() const | Αποκτά το ποσό πληρωμής. |
| [get_BillInformation](./get_billinformation/)() const | Αποκτά τις πρόσθετες δομημένες πληροφορίες τιμολογίου. |
| [get_Creditor](./get_creditor/)() const | Αποκτά τη διεύθυνση του πιστωτή. |
| [get_Currency](./get_currency/)() const | Αποκτά το νόμισμα πληρωμής. |
| [get_Debtor](./get_debtor/)() const | Αποκτά τη διεύθυνση του οφειλέτη. |
| [get_Reference](./get_reference/)() const | Αποκτά την αναφορά πληρωμής του πιστωτή. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Αποκτά το πρόσθετο αδόμητο μήνυμα. |
| [get_Version](./get_version/)() const | Αποκτά την έκδοση του προτύπου SwissQR bill. |
| [GetHashCode](./gethashcode/)() const override | Λαμβάνει τον κώδικα κατακερματισμού για αυτήν την παρουσία. |
| [set_Account](./set_account/)(System::String) | Ορίζει τον αριθμό λογαριασμού του πιστωτή. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Αποκτά ή ορίζει τα εναλλακτικά σχήματα πληρωμής. |
| [set_Amount](./set_amount/)(System::Decimal) | Ορίζει το ποσό πληρωμής. |
| [set_BillInformation](./set_billinformation/)(System::String) | Ορίζει τις πρόσθετες δομημένες πληροφορίες τιμολογίου. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Ορίζει τη διεύθυνση του πιστωτή. |
| [set_Currency](./set_currency/)(System::String) | Ορίζει το νόμισμα πληρωμής. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Ορίζει τη διεύθυνση του οφειλέτη. |
| [set_Reference](./set_reference/)(System::String) | Ορίζει την αναφορά πληρωμής του πιστωτή. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Ορίζει το πρόσθετο αδόμητο μήνυμα. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Ορίζει την έκδοση του προτύπου τιμολογίου SwissQR. |
## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Έκδοση προτύπου τιμολογίου SwissQR |
## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
