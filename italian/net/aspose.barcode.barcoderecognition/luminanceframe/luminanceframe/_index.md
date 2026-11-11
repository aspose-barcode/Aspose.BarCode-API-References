---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "LuminanceFrame constructor. Inizializza una nuova istanza della classe LuminanceFrame senza spaziatura tra le righe. La distanza tra le righe adiacenti è pari a width"
type: docs
weight: 10
url: /it/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Inizializza una nuova istanza della classe [`LuminanceFrame`](../) senza spaziatura tra le righe. La distanza tra le righe adiacenti è pari a *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | Byte[] | I dati di luminanza contenenti un byte per pixel. |
| width | Int32 | La larghezza del fotogramma in pixel. |
| height | Int32 | L'altezza del fotogramma in pixel. |
| rotationDegrees | Int32 | La rotazione in senso orario necessaria per visualizzare il fotogramma in posizione verticale. I valori supportati sono 0, 90, 180 e 270. Il valore predefinito è 0. |

### Vedi anche

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Inizializza una nuova istanza della classe [`LuminanceFrame`](../) con l'intervallo di riga specificato.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | Byte[] | I dati di luminanza contenenti un byte per pixel. |
| width | Int32 | La larghezza del fotogramma in pixel. |
| height | Int32 | L'altezza del fotogramma in pixel. |
| rowStride | Int32 | La distanza in byte tra gli inizi di due righe adiacenti. Il valore non può essere inferiore a *width*. |
| rotationDegrees | Int32 | La rotazione in senso orario necessaria per visualizzare il fotogramma in posizione verticale. I valori supportati sono 0, 90, 180 e 270. |

### Vedi anche

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


