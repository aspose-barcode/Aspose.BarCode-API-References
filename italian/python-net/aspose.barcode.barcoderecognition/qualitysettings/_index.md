---
title: "QualitySettings"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento.<br/>            È possibile impostare rapidamente QualitySettings con preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxQuality oppure configurare manualmente opzioni separate.<br/>            Il valore predefinito di QualitySettings è NormalQuality.

Il tipo QualitySettings espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| high_performance | Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità. |
| normal_quality | Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre |
| high_quality | Preset di qualità di riconoscimento HighQuality. Questo preset è sviluppato per codici a barre di bassa qualità. Consente di rilevare codici a barre altamente danneggiati. |
| max_quality | Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i possibili codici a barre, anche quelli errati. |
| x_dimension | Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |
| minimal_x_dimension | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |
| barcode_quality | Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento. |
| deconvolution | Modalità Deconvolution (restaurazione delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvolution è una funzione che può ripristinare un'immagine degradata <br/>            (convoluta) da qualsiasi funzione naturale come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che corrompe l'immagine, <br/>            dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica. |
| inverse_image | Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza). |
| complex_background | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| allow_incorrect_barcodes | Consente al motore di riconoscere i codici a barre che hanno un checksum errato o valori errati. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato. |

### Vedi anche

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

