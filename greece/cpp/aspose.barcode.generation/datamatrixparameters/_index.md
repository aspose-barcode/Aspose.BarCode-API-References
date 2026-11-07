---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::DataMatrixParameters class. Παράμετροι DataMatrix σε C++."
type: docs
weight: 2000
url: /el/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Παράμετροι DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [get_EccType](./get_ecctype/)() const | Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν το EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. Προεπιλεγμένη τιμή: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με [DataMatrixEccType.Ecc200](../datamatrixecctype/) ή [DataMatrixEccType.EccAuto](../datamatrixecctype/). Δεν μπορούν να χρησιμοποιηθούν με [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Προεπιλεγμένη τιμή: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Αναγνωριστικό Barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [get_Version](./get_version/)() const | Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Ορίζει τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν η EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. Προεπιλεγμένη τιμή: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με [DataMatrixEccType.Ecc200](../datamatrixecctype/) ή [DataMatrixEccType.EccAuto](../datamatrixecctype/). Δεν μπορούν να χρησιμοποιηθούν με [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Προεπιλεγμένη τιμή: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Αναγνωριστικό Barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το [DataMatrixParameters](./). |
## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
