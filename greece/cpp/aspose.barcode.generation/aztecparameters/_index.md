---
title: "Aspose::BarCode::Generation::AztecParameters κλάση"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::AztecParameters κλάση. Παράμετροι Aztec σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Παράμετροι Aztec.

```cpp
class AztecParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [get_ECIEncoding](./get_eciencoding/)() const | Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν το AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Λαμβάνει λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [get_LayersCount](./get_layerscount/)() const | Λαμβάνει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός επιπέδων πρέπει να βρίσκεται στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (αυτόματη). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Aztec. Το αναγνωριστικό barcode πρέπει να βρίσκεται στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. Ο αριθμός barcode πρέπει να βρίσκεται στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά |
| [get_SymbolMode](./get_symbolmode/)() const | Λαμβάνει μια λειτουργία Aztec Symbol mode. Προεπιλεγμένη τιμή: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Ορίζει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός επιπέδων πρέπει να βρίσκεται στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (αυτόματη). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Aztec. Το αναγνωριστικό barcode πρέπει να βρίσκεται στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. Ο αριθμός barcode πρέπει να βρίσκεται στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Ορίζει μια λειτουργία Aztec Symbol mode. Προεπιλεγμένη τιμή: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [AztecParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
