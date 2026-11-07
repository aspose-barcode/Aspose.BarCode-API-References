---
title: "Aspose::BarCode::Generation::DotCodeParameters κλάση"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::DotCodeParameters κλάση. Παράμετροι DotCode σε C++."
type: docs
weight: 2200
url: /el/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Παράμετροι DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [get_Columns](./get_columns/)() const | Καθορίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Καθορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Υποδεικνύει αν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false. |
| [get_Rows](./get_rows/)() const | Καθορίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Καθορίζει το ID του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [set_Columns](./set_columns/)(int32_t) | Καθορίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Καθορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Υποδεικνύει αν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false. |
| [set_Rows](./set_rows/)(int32_t) | Καθορίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Καθορίζει το ID του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DotCodeParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
