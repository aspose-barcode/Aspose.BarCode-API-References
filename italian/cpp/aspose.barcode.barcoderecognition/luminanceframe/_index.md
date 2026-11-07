---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame classe"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame classe. Rappresenta un fotogramma immagine in scala di grigi a 8 bit. Ogni pixel è rappresentato da un byte che contiene il suo valore di luminanza in C++."
type: docs
weight: 2400
url: /it/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Rappresenta un fotogramma di immagine in scala di grigi a 8 bit. Ogni pixel è rappresentato da un byte che contiene il valore della sua luminanza.

```cpp
class LuminanceFrame : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Data](./get_data/)() const | Ottiene i dati di luminanza. |
| [get_Height](./get_height/)() const | Ottiene l'altezza del fotogramma in pixel. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Ottiene il numero di gradi di rotazione in senso orario necessari al fotogramma per avere l'orientamento corretto. |
| [get_RowStride](./get_rowstride/)() const | Ottiene la distanza in byte tra l'inizio di due righe adiacenti. |
| [get_Width](./get_width/)() const | Ottiene la larghezza del fotogramma in pixel. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Inizializza una nuova istanza della classe [LuminanceFrame](./) senza spaziatura tra le righe. La distanza tra le righe adiacenti è pari a *width*. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Inizializza una nuova istanza della classe [LuminanceFrame](./) con la stride di riga specificata. |
## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
