---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κατασκευαστής LuminanceFrame. Αρχικοποιεί μια νέα παρουσία της κλάσης LuminanceFrame χωρίς γεμίσματα μεταξύ των σειρών. Η απόσταση μεταξύ διαδοχικών σειρών είναι ίση με το width"
type: docs
weight: 10
url: /el/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`LuminanceFrame`](../) χωρίς γεμίσματα μεταξύ των σειρών. Η απόσταση μεταξύ διαδοχικών σειρών είναι ίση με το *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | Byte[] | Τα δεδομένα φωτεινότητας που περιέχουν ένα byte ανά pixel. |
| width | Int32 | Το πλάτος του πλαισίου σε pixel. |
| height | Int32 | Το ύψος του πλαισίου σε pixel. |
| rotationDegrees | Int32 | Η δεξιόστροφη περιστροφή που απαιτείται για την ορθή εμφάνιση του πλαισίου. Οι υποστηριζόμενες τιμές είναι 0, 90, 180 και 270. Η προεπιλεγμένη τιμή είναι 0. |

### Δείτε επίσης

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`LuminanceFrame`](../) με το καθορισμένο row stride.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | Byte[] | Τα δεδομένα φωτεινότητας που περιέχουν ένα byte ανά pixel. |
| width | Int32 | Το πλάτος του πλαισίου σε pixel. |
| height | Int32 | Το ύψος του πλαισίου σε pixel. |
| rowStride | Int32 | Η απόσταση σε byte μεταξύ των αρχών δύο διαδοχικών γραμμών. Η τιμή δεν μπορεί να είναι μικρότερη από *width*. |
| rotationDegrees | Int32 | Η δεξιόστροφη περιστροφή που απαιτείται για να εμφανιστεί το πλαίσιο όρθιο. Οι υποστηριζόμενες τιμές είναι 0, 90, 180 και 270. |

### Δείτε επίσης

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


