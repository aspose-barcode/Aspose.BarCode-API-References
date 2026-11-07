---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings classe"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings classe. QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings con i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxQuality oppure configurare manualmente le singole opzioni. Il valore predefinito di QualitySettings è NormalQuality in C++."
type: docs
weight: 3100
url: /it/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Consente al motore di riconoscere i codici a barre che hanno checksum o valori errati. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento. |
| [get_ComplexBackground](./get_complexbackground/)() const | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| [get_Deconvolution](./get_deconvolution/)() const | Modalità di deconvoluzione (restauro delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale come il blur, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione che corrompe l'immagine, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica. |
| static [get_HighPerformance](./get_highperformance/)() | Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità. |
| static [get_HighQuality](./get_highquality/)() | Preset di qualità di riconoscimento HighQuality. Questo preset è sviluppato per codici a barre di bassa qualità. Consente di rilevare codici a barre altamente danneggiati. |
| [get_InverseImage](./get_inverseimage/)() const | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza). |
| static [get_MaxQuality](./get_maxquality/)() | Preset di qualità di riconoscimento MaxQuality. Questo preset è stato sviluppato per riconoscere tutti i codici a barre possibili, anche i codici a barre errati. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre |
| [get_XDimension](./get_xdimension/)() const | Modalità [Recognition](../../aspose.barcode.barcoderecognition.recognition/) che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella di matrice o barra. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Consente al motore di riconoscere i codici a barre che hanno checksum o valori errati. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Modalità di deconvoluzione (restauro delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale come il blur, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione che corrompe l'immagine, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Modalità [Recognition](../../aspose.barcode.barcoderecognition.recognition/) che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella di matrice o barra. |
## Osservazioni


Questo esempio mostra come utilizzare [QualitySettings](./) con [BarCodeReader](../barcodereader/)
```cpp
[C#]
//imposta la modalità di riconoscimento HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//imposta la modalità di riconoscimento HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//imposta la modalità di riconoscimento HighPerformance per codici a barre di piccole dimensioni
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//imposta la modalità di riconoscimento HighPerformance per codici a barre di bassa qualità
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
