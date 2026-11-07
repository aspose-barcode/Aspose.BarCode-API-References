---
title: "Namespace Aspose::BarCode::BarCodeRecognition"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Come utilizzare il namespace Aspose::BarCode::BarCodeRecognition in C++."
type: docs
weight: 200
url: /it/cpp/aspose.barcode.barcoderecognition/
---



## Classi

| Classe | Descrizione |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Interfaccia pubblica per la decodifica del campo Customer Information, utilizzata nella simbologia AustraliaPost. L'implementazione deve essere fornita dall'utente. |
| [AustraliaPostSettings](./australiapostsettings/) | Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Memorizza dati speciali del codice a barre Aztec riconosciuto |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Memorizza parametri estesi del codice a barre riconosciuto |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre |
| [BarCodeResult](./barcoderesult/) | Memorizza i dati del codice a barre riconosciuto come tipo [SingleDecodeType](./singledecodetype/), testo del codice **System::String**, regione [BarCodeRegionParameters](./barcoderegionparameters/) e altri parametri |
| [BarcodeSettings](./barcodesettings/) | I principali parametri di decodifica [BarCode](../aspose.barcode/). Contiene parametri che influenzano i dati riconosciuti. |
| [BaseDecodeType](./basedecodetype/) | Classe base per [MultiDecodeType](./multidecodetype/) e [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Classe di base per la memorizzazione di parametri estesi del codice a barre riconosciuto |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Memorizza informazioni aggiuntive Codabar del codice a barre riconosciuto |
| [Code128DataPortion](./code128dataportion/) | Contiene i dati del sottotipo per il codice a barre di tipo Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Memorizza dati speciali del codice a barre Code128 riconosciuto |
| [DataBarExtendedParameters](./databarextendedparameters/) | Memorizza informazioni aggiuntive DataBar del codice a barre riconosciuto |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Memorizza dati speciali del codice a barre [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) riconosciuto |
| [DecodeType](./decodetype/) | Specifica il tipo di codice a barre da leggere. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Eccezione generale lanciata da [BarCodeReader](./barcodereader/), ereditata da BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Rappresenta l'eccezione di interruzione del riconoscimento che viene lanciata al superamento del timeout durante il riconoscimento con [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Memorizza dati speciali del codice a barre DotCode riconosciuto |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Memorizza dati speciali del codice a barra **GS1 Composite Bar** riconosciuto |
| [Iso15416Quality](./iso15416quality/) | Memorizza i gradi di qualità del codice a barre calcolati secondo lo standard ISO/IEC 15416 per i codici a barre 1D. |
| [IsoSymbolQuality](./isosymbolquality/) | Memorizza i risultati della valutazione della qualità del simbolo del codice a barre secondo gli standard ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Rappresenta un fotogramma di immagine in scala di grigi a 8 bit. Ogni pixel è rappresentato da un byte che contiene il valore della sua luminanza. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Memorizza informazioni aggiuntive MaxiCode del codice a barre riconosciuto |
| [MultiDecodeType](./multidecodetype/) | Tipo di decodifica composita. |
| [OneDExtendedParameters](./onedextendedparameters/) | Memorizza dati speciali del codice a barre 1D riconosciuto, come testo del codice separato e checksum |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto |
| [QRExtendedParameters](./qrextendedparameters/) | Memorizza informazioni Structured Append del [QR](../aspose.barcode.barcoderecognition.qr/) del codice a barre riconosciuto |
| [Quadrangle](./quadrangle/) | Memorizza un insieme di quattro [Point](../) che rappresentano una regione [Quadrangle](./quadrangle/). |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente [QualitySettings](./qualitysettings/) con le preimpostazioni incorporate: HighPerformance, NormalQuality, HighQuality, MaxQuality oppure configurare manualmente le opzioni separate. Il valore predefinito di [QualitySettings](./qualitysettings/) è NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Tipo di decodifica singola. Vedi il tipo di decodifica per ottenere l'istanza. |
## Enums

| Enumerazione | Descrizione |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Contiene i tipi del sottoinsieme Code128 |
| [BarCodeConfidence](./barcodeconfidence/) | Contiene il livello di fiducia del riconoscimento |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
