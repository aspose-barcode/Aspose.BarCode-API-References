---
title: "Aspose::BarCode::Generation::BaseGenerationParameters class"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::BaseGenerationParameters class. Parametri di generazione dell'immagine del codice a barre in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class


Parametri di generazione dell'immagine del codice a barre.

```cpp
class BaseGenerationParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AutoSizeMode](./get_autosizemode/)() const | Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: [AutoSizeMode.None](../autosizemode/). |
| [get_BackColor](./get_backcolor/)() const | Colore di sfondo dell'immagine del codice a barre. Valore predefinito: Color.White. Vedi [Color](../). |
| [get_Barcode](./get_barcode/)() const | Ottiene i [BarcodeParameters](../barcodeparameters/) che contengono tutte le proprietà del codice a barre. |
| [get_Border](./get_border/)() const | Ottiene i [BorderParameters](../borderparameters/) che contengono tutte le proprietà di configurazione per il bordo del codice a barre. |
| [get_CaptionAbove](./get_captionabove/)() const | Didascalia sopra l'immagine [BarCode](../../aspose.barcode/). Vedi [CaptionParameters](../captionparameters/). |
| [get_CaptionBelow](./get_captionbelow/)() const | Didascalia sotto l'immagine [BarCode](../../aspose.barcode/). Vedi [CaptionParameters](../captionparameters/). |
| [get_Image](./get_image/)() const | Parametri dell'immagine. Vedi [ImageParameters](../imageparameters/). |
| [get_ImageHeight](./get_imageheight/)() const | Altezza dell'immagine [BarCode](../../aspose.barcode/) quando la proprietà [AutoSizeMode](../autosizemode/) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_ImageWidth](./get_imagewidth/)() const | Larghezza dell'immagine [BarCode](../../aspose.barcode/) quando la proprietà [AutoSizeMode](../autosizemode/) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_Resolution](./get_resolution/)() const | Ottiene la risoluzione dell'immagine [BarCode](../../aspose.barcode/). Un unico valore per entrambe le dimensioni. Valore predefinito: 96 dpi. |
| [get_RotationAngle](./get_rotationangle/)() const | Angolo di rotazione dell'immagine [BarCode](../../aspose.barcode/), misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 indica nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0. |
| [get_UseAntiAlias](./get_useantialias/)() const | Ottiene un valore che indica se è usata la modalità anti-aliasing per renderizzare l'immagine |
| [set_AutoSizeMode](./set_autosizemode/)(Aspose::BarCode::Generation::AutoSizeMode) | Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: [AutoSizeMode.None](../autosizemode/). |
| [set_BackColor](./set_backcolor/)(System::Drawing::Color) | Colore di sfondo dell'immagine del codice a barre. Valore predefinito: Color.White. Vedi [Color](../). |
| [set_ImageHeight](./set_imageheight/)(System::SharedPtr\<Unit\>) | Altezza dell'immagine [BarCode](../../aspose.barcode/) quando la proprietà [AutoSizeMode](../autosizemode/) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_ImageWidth](./set_imagewidth/)(System::SharedPtr\<Unit\>) | Larghezza dell'immagine [BarCode](../../aspose.barcode/) quando la proprietà [AutoSizeMode](../autosizemode/) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_Resolution](./set_resolution/)(float) | Imposta la risoluzione dell'immagine [BarCode](../../aspose.barcode/). Un unico valore per entrambe le dimensioni. Valore predefinito: 96 dpi. |
| [set_RotationAngle](./set_rotationangle/)(float) | Angolo di rotazione dell'immagine [BarCode](../../aspose.barcode/), misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 indica nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0. |
| [set_UseAntiAlias](./set_useantialias/)(bool) | Imposta un valore che indica se è usata la modalità anti-aliasing per renderizzare l'immagine |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
