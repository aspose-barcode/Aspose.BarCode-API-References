---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Lo spazio dei nomi aspose.barcode offre classi ed enum per creare, personalizzare e decodificare una vasta gamma di tipi di codici a barre in Node.js via Java."
type: docs
weight: 10
url: /it/nodejs/aspose.barcode/
---
Utilizza questi tipi per configurare le impostazioni di generazione dei codici a barre, come la formattazione degli indirizzi, le specifiche regionali e i parametri avanzati per Aztec e altre simbologie. Lo spazio dei nomi include helper per costruire testi di codice estesi e gestire standard postali specializzati.

## Classi

| Classe | Descrizione |
| --- | --- |
| [Address](./address/) | Indirizzo del creditore o del debitore. È possibile impostare via, numero civico, codice postale e città (tipo indirizzo strutturato) o |
| [AlternativeScheme](./alternativescheme/) | Istruzioni per lo schema di pagamento alternativo |
| [AustraliaPostSettings](./australiapostsettings/) | Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost |
| [AustralianPostParameters](./australianpostparameters/) | Parametri del codice a barre AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Generatore di codetext esteso per codici a barre Aztec per la modalità ExtendedCodetext di AztecEncodeMode. Usa la proprietà TwoDDisplayText |
| [AztecExtendedParameters](./aztecextendedparameters/) | Memorizza dati speciali del codice a barre Aztec riconosciuto. Questo esempio mostra come ottenere i valori grezzi Aztec let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Parametri Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Memorizza parametri estesi del codice a barre riconosciuto |
| [BarCodeReader](./barcodereader/) | BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre |
| [BarCodeResult](./barcoderesult/) | Memorizza i dati del codice a barre riconosciuto come tipo SingleDecodeType, `string` codetext, BarCodeRegionParameters region e altri p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator per la generazione di immagini di codici a barre backend. simbologie supportate: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Parametri di generazione del Barcode. |
| [BarcodeSettings](./barcodesettings/) | I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parametri di generazione dell'immagine Barcode. |
| [BorderParameters](./borderparameters/) | Parametri del bordo dell'immagine Barcode |
| [CMYKColor](./cmykcolor/) | Classe per il colore CMYK. Un'istanza null significa che il CMYK non è usato e il colore RGB predefinito è in uso. |
| [CaptionParameters](./captionparameters/) | Parametri della didascalia. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Memorizza informazioni aggiuntive Codabar del barcode riconosciuto |
| [CodabarParameters](./codabarparameters/) | Parametri Codabar. |
| [CodablockParameters](./codablockparameters/) | Parametri Codablock. |
| [Code128DataPortion](./code128dataportion/) | Contiene i dati del sottotipo per il barcode di tipo Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Memorizza dati speciali del barcode Code128 riconosciuto. Rappresenta la regione del barcode riconosciuto e l'angolo del barcode. |
| [Code128Parameters](./code128parameters/) | Parametri Code128. |
| [Code16KParameters](./code16kparameters/) | Parametri Code16K. |
| [CodetextParameters](./codetextparameters/) | Parametri Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator per la generazione di immagini di barcode complessi backend (ad es. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader decodifica il codetext al tipo di barcode complesso specificato. |
| [CouponParameters](./couponparameters/) | Parametri Coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Memorizza informazioni aggiuntive DataBar del barcode riconosciuto |
| [DataBarParameters](./databarparameters/) | Parametri Databar. |
| [DataElement](./dataelement/) | Rappresenta un campo dati specifico per giurisdizione usato nei documenti, ad esempio ElementID = "ZVA" con Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Generatore di codetext esteso per barcode DataMatrix 2D per la modalità ExtendedCodetext di DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Memorizza dati speciali del barcode DataMatrix riconosciuto. Questo esempio mostra come ottenere i valori grezzi DataMatrix; let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | Parametri DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Generatore di codetext esteso per barcode DotCode 2D per la modalità ExtendedCodetext di DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Memorizza dati speciali del barcode DotCode riconosciuto. Questo esempio mostra come ottenere i valori grezzi DotCode |
| [DotCodeParameters](./dotcodeparameters/) | Parametri DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Classe di supporto per la generazione automatica di codetext della Extended Codetext Mode |
| [FontUnit](./fontunit/) | Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile dove la dimensione è nella proprietà Unit value. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Memorizza dati speciali del codice a barre riconosciuto `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Parametri GS1 Composite bar. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari e secondari. Questo camp |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC. Questo esempio mostra come decodificare il raw HIBC LI |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari. Questo esempio mostra come |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati secondari. |
| [HIBCPASCodetext](./hibcpascodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Classe per la memorizzazione del record HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Generatore di codetext esteso per Han Xin Code per la Modalità Estesa di HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Parametri Han Xin. |
| [HslaColor](./hslacolor/) | Classe per rappresentare il colore HSLA (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Interfaccia per codetext complesso usato con ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | Parametri ITF. |
| [ImageParameters](./imageparameters/) | Parametri immagine. |
| [License](./license/) | Fornisce metodi per licenziare il componente. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Classe per la codifica e decodifica del testo incorporato nel codice Royal Mailmark a 4 stati. |
| [MandatoryFields](./mandatoryfields/) | Elementi obbligatori (campi) della carta |
| [MaxiCodeCodetext](./maxicodecodetext/) | Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode. Questo esempio mostra come decodificare il raw MaxiCod |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Classe per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Classe per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 3. Questo esempio mostra come codificare e |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Generatore di codetext esteso per i codici a barre MaxiCode per la Modalità ExtendedCodetext di MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Memorizza informazioni aggiuntive MaxiCode del codice a barre riconosciuto |
| [MaxiCodeParameters](./maxicodeparameters/) | Parametri MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Classe per la codifica e decodifica del secondo messaggio standard per il codice a barre MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Classe per la codifica e decodifica del secondo messaggio standard per il codice a barre MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Classe per la codifica e decodifica del secondo messaggio strutturato per il codice a barre MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Memorizza dati speciali del codice a barre 1D riconosciuto, come codetext separato e checksum |
| [OptionalFields](./optionalfields/) | Elementi opzionali (campi) della carta |
| [Padding](./padding/) | Parametri di padding. |
| [PatchCodeParameters](./patchcodeparameters/) | Parametri PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto |
| [Pdf417Parameters](./pdf417parameters/) | Parametri PDF417. Contiene parametri PDF417, MacroPDF417, MicroPDF417 e GS1MicroPdf417. MacroPDF417 richiede due fie |
| [PdfParameters](./pdfparameters/) | Wrapper dei parametri PDF. Si aspetta un'istanza `mwObject` sottostante che fornisce i metodi getter/setter corrispondenti |
| [PostalParameters](./postalparameters/) | Parametri postali. Utilizzati per Postnet, Planet. |
| [PrimaryData](./primarydata/) | Classe per la memorizzazione dei dati primari HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | Memorizza informazioni QR Structured Append del codice a barre riconosciuto |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Generatore di codetext esteso per codici QR 2D per la modalità ExtendedCodetext di QREncodeMode. Usa la proprietà Display2DText di B |
| [QrParameters](./qrparameters/) | Parametri QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | Parametri QR structured append. |
| [Quadrangle](./quadrangle/) | Memorizza un insieme di quattro punti che rappresentano una regione quadrilatero. |
| [QualitySettings](./qualitysettings/) | QualitySettings consente di configurare manualmente la qualità e la velocità di riconoscimento. Puoi impostare rapidamente QualitySettings tramite em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Rappresenta l'eccezione di interruzione del riconoscimento che viene sollevata al superamento del timeout durante il riconoscimento con BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Classe per la memorizzazione dei dati secondari e aggiuntivi HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | Le proprietà del sottofile USA DL, offset e lunghezza, sono impostate automaticamente. |
| [SupplementParameters](./supplementparameters/) | Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | Parametri SVG. |
| [SwissQRBill](./swissqrbill/) | Dati della fattura SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Classe per la codifica e la decodifica del testo incorporato nel codice PDF417 della patente di guida USA. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Classe per i campi specifici della giurisdizione per la patente USA |
| [Unit](./unit/) | Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.). |
