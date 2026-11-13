---
title: "BaseGenerationParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Parametri di generazione dell'immagine barcode.

Il tipo BaseGenerationParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| use_anti_alias | Ottiene o imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine |
| back_color | Colore di sfondo dell'immagine del codice a barre.<br/>            Valore predefinito: Color.White.<br/>            Vedi [Color](/barcode/python-net/aspose.drawing/color/). |
| risoluzione | Ottiene o imposta la risoluzione dell'immagine BarCode.<br/>            Un valore per entrambe le dimensioni.<br/>            Valore predefinito: 96 dpi. |
| rotation_angle | Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione.<br/>            Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine.<br/>            Valore predefinito: 0. |
| caption_above | Didascalia sopra l'immagine BarCode. Vedi [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Didascalia sotto l'immagine BarCode. Vedi [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Parametri immagine. Vedi [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Specifica i diversi tipi di modalità di dimensionamento automatico.<br/>            Valore predefinito: AutoSizeMode.None. |
| image_height | Altezza dell'immagine BarCode quando la proprietà [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| image_width | Larghezza dell'immagine BarCode quando la proprietà [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| barcode | Ottiene i [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) che contengono tutte le proprietà del codice a barre. |
| border | Ottiene i [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) che contengono tutte le proprietà di configurazione per il bordo del codice a barre. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

