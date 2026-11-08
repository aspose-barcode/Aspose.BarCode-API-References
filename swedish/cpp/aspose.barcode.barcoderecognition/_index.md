---
title: "Aspose::BarCode::BarCodeRecognition namnrymd"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::BarCodeRecognition namnrymd i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode.barcoderecognition/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Publikt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost-symbologi. Implementering bör tillhandahållas av användaren. |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost-avkodningsparametrar. Innehåller parametrar som påverkar den avkodade datan för AustraliaPost-symbologi. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Lagrar speciella data för Aztec-avläst streckkod |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Lagrar utökade parametrar för avläst streckkod |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) kapslar in en bild som kan innehålla en eller flera streckkoder, den kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Representerar den avlästa streckkodens region och streckkodsvinkel |
| [BarCodeResult](./barcoderesult/) | Lagrar avläst streckkoddata såsom typ [SingleDecodeType](./singledecodetype/), **System::String** kodtext, region [BarCodeRegionParameters](./barcoderegionparameters/) och andra parametrar |
| [BarcodeSettings](./barcodesettings/) | De huvudsakliga avkodningsparametrarna för [BarCode](../aspose.barcode/). Innehåller parametrar som påverkar den avlästa datan. |
| [BaseDecodeType](./basedecodetype/) | Basklass för [MultiDecodeType](./multidecodetype/) och [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Grundklass för lagring av utökade parametrar för avläst streckkod |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Lagrar ytterligare information för Codabar för avläst streckkod |
| [Code128DataPortion](./code128dataportion/) | Innehåller data för undertypen av Code128-typ streckkod |
| [Code128ExtendedParameters](./code128extendedparameters/) | Lagrar speciella data för avläst Code128-streckkod |
| [DataBarExtendedParameters](./databarextendedparameters/) | Lagrar ytterligare information för DataBar för avläst streckkod |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Lagrar speciella data för avläst [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) streckkod |
| [DecodeType](./decodetype/) | Ange typen av streckkod att läsa. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Allmänt undantag som kastas av [BarCodeReader](./barcodereader/), ärvt från BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Representerar avbrytningsundantag för avkodning som kastas vid tidsgränsen överskrids under avkodning med [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Lagrar speciella data för avläst DotCode-streckkod |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Lagrar speciella data för avläst **GS1 Composite Bar** streckkod |
| [Iso15416Quality](./iso15416quality/) | Lagrar streckkodskvalitetsgrader beräknade enligt ISO/IEC 15416-standarden för 1D-streckkoder. |
| [IsoSymbolQuality](./isosymbolquality/) | Lagrar resultat för streckkodssymbolens kvalitetsutvärdering enligt ISO/IEC-standarder. |
| [LuminanceFrame](./luminanceframe/) | Representerar en 8-bitars gråskalebildram. Varje pixel representeras av en byte som innehåller dess luminansvärde. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Lagrar ytterligare information för MaxiCode för den igenkända streckkoden. |
| [MultiDecodeType](./multidecodetype/) | Sammansatt avkodningstyp. |
| [OneDExtendedParameters](./onedextendedparameters/) | Lagrar speciella data för 1D-igenkänd streckkod, såsom separat kodtext och kontrollsumma. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Lagrar metadatainformation för MacroPdf417 för den igenkända streckkoden. |
| [QRExtendedParameters](./qrextendedparameters/) | Lagrar en [QR](../aspose.barcode.barcoderecognition.qr/) Structured Append-information för den igenkända streckkoden. |
| [Quadrangle](./quadrangle/) | Lagrar en uppsättning av fyra [Point](../)s som representerar ett [Quadrangle](./quadrangle/)-område. |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) gör det möjligt att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in [QualitySettings](./qualitysettings/) med inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxQuality eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för [QualitySettings](./qualitysettings/) är NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Enkel avkodningstyp. Se avkodningstyp för att få en instans. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Innehåller typer av Code128-undermängd. |
| [BarCodeConfidence](./barcodeconfidence/) | Innehåller igenkänningskonfidensnivå. |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
