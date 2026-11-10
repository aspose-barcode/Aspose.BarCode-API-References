---
title: "Κλάση DataMatrixParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.DataMatrixParameters. Παράμετροι DataMatrix"
type: docs
weight: 1220
url: /el/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

Παράμετροι DataMatrix.

```csharp
public class DataMatrixParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Αναλογία Ύψος/Πλάτος του 2D BarCode μονάδας. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Λαμβάνει ή ορίζει έναν τύπο Datamatrix ECC. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Λαμβάνει ή ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν η EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Λειτουργία κωδικοποίησης του Datamatrix barcode. Προεπιλεγμένη τιμή: EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. Προεπιλεγμένη τιμή: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με DataMatrixEccType.Ecc200 ή DataMatrixEccType.EccAuto. Δεν μπορεί να χρησιμοποιηθεί με EncodeTypes.GS1DataMatrix Προεπιλεγμένη τιμή: MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Αναγνωριστικό Barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Αριθμός Barcodes για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | Αναγνωριστικό αρχείου (File ID) για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `DataMatrixParameters`. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


