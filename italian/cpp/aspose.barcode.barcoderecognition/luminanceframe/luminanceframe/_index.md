---
title: "costruttore"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "costruttore. Inizializza una nuova istanza della classe LuminanceFrame senza spaziatura tra le righe. La distanza tra righe adiacenti è pari a width in C++."
type: docs
weight: 600
url: /it/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Inizializza una nuova istanza della classe [LuminanceFrame](../) senza spaziatura tra le righe. La distanza tra righe adiacenti è pari a *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | I dati di luminanza contenenti un byte per pixel. |
| width | int32_t | La larghezza del frame in pixel. |
| height | int32_t | L'altezza del frame in pixel. |
| rotationDegrees | int32_t | La rotazione in senso orario necessaria per visualizzare il frame in posizione verticale. I valori supportati sono 0, 90, 180 e 270. Il valore predefinito è 0. |

## Vedi anche

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Inizializza una nuova istanza della classe [LuminanceFrame](../) con la distanza di riga specificata.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | I dati di luminanza contenenti un byte per pixel. |
| width | int32_t | La larghezza del frame in pixel. |
| height | int32_t | L'altezza del frame in pixel. |
| rowStride | int32_t | La distanza in byte tra gli inizi di due righe adiacenti. Il valore non può essere inferiore a *width*. |
| rotationDegrees | int32_t | La rotazione in senso orario necessaria per visualizzare il fotogramma in posizione verticale. I valori supportati sono 0, 90, 180 e 270. |

## Vedi anche

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
