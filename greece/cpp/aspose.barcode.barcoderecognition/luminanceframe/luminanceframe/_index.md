---
title: "Κατασκευαστής"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " κατασκευαστής. Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LuminanceFrame χωρίς γεμίσματα μεταξύ των γραμμών. Η απόσταση μεταξύ διαδοχικών γραμμών είναι ίση με το πλάτος σε C++."
type: docs
weight: 600
url: /el/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LuminanceFrame](../) χωρίς γεμίσματα μεταξύ των γραμμών. Η απόσταση μεταξύ διαδοχικών γραμμών είναι ίση με το *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Τα δεδομένα φωτεινότητας που περιέχουν ένα byte ανά pixel. |
| width | int32_t | Το πλάτος του πλαισίου σε pixels. |
| height | int32_t | Το ύψος του πλαισίου σε pixels. |
| rotationDegrees | int32_t | Η δεξιόστροφη περιστροφή που απαιτείται για να εμφανιστεί το πλαίσιο όρθιο. Οι υποστηριζόμενες τιμές είναι 0, 90, 180 και 270. Η προεπιλεγμένη τιμή είναι 0. |

## Δείτε επίσης

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LuminanceFrame](../) με το καθορισμένο row stride.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Τα δεδομένα φωτεινότητας που περιέχουν ένα byte ανά pixel. |
| width | int32_t | Το πλάτος του πλαισίου σε pixels. |
| height | int32_t | Το ύψος του πλαισίου σε pixels. |
| rowStride | int32_t | Η απόσταση σε bytes μεταξύ των αρχών δύο διαδοχικών γραμμών. Η τιμή δεν μπορεί να είναι μικρότερη από *width* . |
| rotationDegrees | int32_t | Η δεξιόστροφη περιστροφή που απαιτείται για να εμφανιστεί το πλαίσιο όρθιο. Οι υποστηριζόμενες τιμές είναι 0, 90, 180 και 270. |

## Δείτε επίσης

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
