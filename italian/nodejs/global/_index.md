---
title: "Globale"
linktitle: "Globale"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Lo spazio dei nomi Global raggruppa le enumerazioni di base e le classi di utilità utilizzate in Aspose.BarCode per Node.js via Java."
type: docs
weight: 20
url: /it/nodejs/global/
---
Lo spazio dei nomi Global fornisce una raccolta di enumerazioni fondamentali e tipi di supporto che definiscono le proprietà dei codici a barre come modalità di codifica, dimensioni dei simboli, livelli di confidenza e formati immagine. Queste definizioni sono richiamate in tutta l'API Aspose.BarCode per configurare e interpretare la generazione e il riconoscimento dei codici a barre.

## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [AddressType](./addresstype/) | Tipo di indirizzo |
| [AutoSizeMode](./autosizemode/) | Specifica i diversi tipi di modalità di dimensionamento automatico. Il valore predefinito è AutoSizeMode.NONE. |
| [AztecEncodeMode](./aztecencodemode/) | Modalità di codifica per i codici a barre Aztec. |
| [AztecSymbolMode](./aztecsymbolmode/) | Specifica la modalità del simbolo Aztec. |
| [BarCodeConfidence](./barcodeconfidence/) | Contiene il livello di confidenza del riconoscimento |
| [BarCodeImageFormat](./barcodeimageformat/) | Specifica il formato file dell'immagine. |
| [BarcodeClassifications](./barcodeclassifications/) | Classificazione BarcodeClassifications EncodeTypes |
| [BarcodeQualityMode](./barcodequalitymode/) | Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Elemento del codice a barre con qualità inferiore r |
| [BorderDashStyle](./borderdashstyle/) | Specifica lo stile delle linee di bordo tratteggiate. |
| [ChecksumValidation](./checksumvalidation/) | Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono cont |
| [CodabarChecksumMode](./codabarchecksummode/) | Specifica l'algoritmo di checksum per Codabar |
| [CodabarSymbol](./codabarsymbol/) | Specifica il simbolo di inizio o fine della specifica del codice a barre Codabar. |
| [Code128EncodeMode](./code128encodemode/) | Modalità di codifica per i codici a barre Code128. Specifica `Code 128`. Questo codice dimostra come generare il code 128 con diffe |
| [Code128SubType](./code128subtype/) | Contiene i tipi del sottoinsieme Code128 |
| [CodeLocation](./codelocation/) | Posizione del testo del codice |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. Questo esempio mostra come utilizzare Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Definisce il tipo di interpretazione (C_TABLE o N_TABLE) delle informazioni cliente per AustralianPost BarCode. |
| [DataMatrixEccType](./datamatrixecctype/) | Specifica il tipo di ECC da codificare. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | Modalità di codifica dell'encoder DataMatrix, predefinita su Auto. Questo esempio mostra come gestire il codetext in Modalità Estesa. //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | Specifica il tipo di ECC da codificare. |
| [DecodeType](./decodetype/) | Specifica il tipo di codice a barre da leggere. |
| [DeconvolutionMode](./deconvolutionmode/) | Modalità deconvoluzione (restauro immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Modalità di codifica per i codici a barre DotCode. |
| [ECIEncodings](./eciencodings/) | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [EnableChecksum](./enablechecksum/) | Abilita il checksum durante la generazione per i codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum |
| [EncodeTypes](./encodetypes/) | Specifica il tipo di codice a barre da codificare. |
| [FontMode](./fontmode/) | Modalità dimensione carattere. |
| [FontStyle](./fontstyle/) | Classificazione FontStyle |
| [GraphicsUnit](./graphicsunit/) | Specifica l'unità di misura per i dati forniti. |
| [HIBCLICDateFormat](./hibclicdateformat/) | Specifica i diversi tipi di formati data per HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Tipi di posizione dati HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Tipi di dati del record HIBC PAS. |
| [HanXinEncodeMode](./hanxinencodemode/) | Modalità di codifica Han Xin Code. Si consiglia di usare Auto con caratteri ASCII / Cinesi o Unicode per i caratteri Unicode |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Livello di correzione errori Reed-Solomon. Da basso ad alto: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Versione di Han Xin Code. Da Version01 - 23 x 23 moduli a Version84 - 189 x 189 moduli, aumentando di 2 moduli per passo |
| [ITF14BorderType](./itf14bordertype/) | Tipo di bordo del codice a barre ITF14 |
| [InverseImageMode](./inverseimagemode/) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza). Questo esempio |
| [MacroCharacter](./macrocharacter/) | I valori dei Macro Caratteri 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Il Macro carattere 05 è trans |
| [Mailmark2DType](./mailmark2dtype/) | Il Tipo Mailmark 2D definisce la dimensione del codice a barre Data Matrix |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Modalità di codifica per i codici a barre MaxiCode. |
| [MaxiCodeMode](./maxicodemode/) | Modalità di codifica per i codici a barre MaxiCode. |
| [MicroQRVersion](./microqrversion/) | Versione di MicroQR Code. Da M1 a M4. |
| [PatchFormat](./patchformat/) | Formato PatchCode. Scegli PatchOnly per generare un singolo PatchCode. Usa il formato page per generare la pagina Patch con i PatchCode. |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Modalità di compattazione del codice a barre Pdf417. |
| [Pdf417EncodeMode](./pdf417encodemode/) | Modalità di codifica del codice a barre Pdf417. |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | Livello di correzione degli errori del codice a barre pdf417, da livello 0 a livello 9, il livello 0 significa nessuna correzione degli errori, il livello 9 è il migliore. |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Utilizzato per indicare al codificatore se aggiungere il Terminatore Macro PDF417 (codeword 922) al segmento. Applicato solo per Macro PD. |
| [QREncodeMode](./qrencodemode/) | Modalità di codifica per i codici a barre QR. Esempio di utilizzo della codifica ECI generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | Modalità di selezione QR / MicroQR. Seleziona FORCE_QR per i simboli QR standard, AUTO per MicroQR. FORCE_MICRO_QR è usato per forte |
| [QRErrorLevel](./qrerrorlevel/) | Livello di correzione degli errori Reed-Solomon. Da basso a alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | Versione del QR Code. Da Version1 a Version40 per il QR code e da M1 a M4 per MicroQr. |
| [QrBillStandardVersion](./qrbillstandardversion/) | Versione standard del bollettino SwissQR |
| [QrExtCompactionMode](./qrextcompactionmode/) | Specifica la modalità di compattazione QR per il testo codificato aggiunto da QrExtCodetextBuilder. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Versione del codice RectMicroQR. Dalla versione R7x43 alla versione R17x139. |
| [SvgColorMode](./svgcolormode/) | Modalità possibili per il riempimento del colore in un file svg, RGB è predefinito e supportato da SVG 1.1. RGBA, HSL, HSLA sono consentiti in SVG. |
| [TextAlignment](./textalignment/) | Allineamento del testo. |
