---
title: Aspose.BarCode.Generation
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Il Aspose.BarCode.Generation contenente classi generali per limplementazione di funzioni di generazione BarCode.
type: docs
weight: 50
url: /it/net/aspose.barcode.generation/
---
Il **Aspose.BarCode.Generation** contenente classi generali per l'implementazione di funzioni di generazione BarCode.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | Parametri del codice a barre AustralianPost. |
| [AztecParameters](./aztecparameters) | parametri aztechi. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator per la generazione di immagini di codici a barre back-end. |
| [BarcodeParameters](./barcodeparameters) | Parametri di generazione del codice a barre. |
| [BaseEncodeType](./baseencodetype) | Classe base per SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Parametri di generazione dell'immagine del codice a barre. |
| [BorderParameters](./borderparameters) | Parametri del bordo dell'immagine del codice a barre |
| [CaptionParameters](./captionparameters) | Parametri didascalia. |
| [CodabarParameters](./codabarparameters) | Parametri Codabar. |
| [CodablockParameters](./codablockparameters) | Parametri blocco codice. |
| [Code16KParameters](./code16kparameters) | Code16K parametri. |
| [CodetextParameters](./codetextparameters) | Parametri testo codice. |
| [CouponParameters](./couponparameters) | Parametri del buono. Utilizzato per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Parametri della barra dati. |
| [DataMatrixParameters](./datamatrixparameters) | Parametri DataMatrix. |
| [DotCodeParameters](./dotcodeparameters) | Parametri DotCode. |
| [EncodeTypes](./encodetypes) | Specifica il tipo di codice a barre da codificare. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Classe helper per la generazione automatica del testo del codice della modalità testo del codice esteso |
| [FontUnit](./fontunit) | Definisce un formato particolare per il testo, inclusi il tipo di carattere, le dimensioni e gli attributi di stile dove dimensione nella proprietà Valore unità. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | GS1 Parametri della barra composita. |
| [ITFParameters](./itfparameters) | Parametri ITF. |
| [MaxiCodeParameters](./maxicodeparameters) | parametri MaxiCode. |
| [Padding](./padding) | Parametri di riempimento. |
| [PatchCodeParameters](./patchcodeparameters) | Parametri PatchCode. |
| [Pdf417Parameters](./pdf417parameters) | parametri PDF417. Contiene i parametri PDF417, MacroPDF417 e MicroPDF417. MacroPDF417 richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi. MicroPDF417 in modalità di aggiunta strutturata (uguale alla modalità MacroPDF417) richiede due campi: Pdf417MacroFileID e Pdf417MacroSegmentID. Tutti gli altri campi sono facoltativi. |
| [PostalParameters](./postalparameters) | Parametri postali. Usato per Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Generatore di codetext esteso per codici a barre QR 2D per la modalità ExtendedCodetext di QrEncodeMode |
| [QrParameters](./qrparameters) | Parametri QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | QR strutturato append parametri. |
| [SupplementParameters](./supplementparameters) | Supplemento parametri. Utilizzato per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Tipo di codifica simbologia. Vedere EncodeTypes per ottenere l'istanza. |
| [Unit](./unit) | Specifica il valore della dimensione in diverse unità (Pixel, Pollici, ecc.). |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Specifica i diversi tipi di modalità di ridimensionamento automatico. |
| [AztecSymbolMode](./aztecsymbolmode) | Specifica la modalità del simbolo azteco. |
| [BarcodeClassifications](./barcodeclassifications) | Classificazione simbologia |
| [BarCodeImageFormat](./barcodeimageformat) | Specifica il formato file dell'immagine. |
| [BorderDashStyle](./borderdashstyle) | Specifica lo stile delle linee di bordo tratteggiate. |
| [CodabarChecksumMode](./codabarchecksummode) | Specifica l'algoritmo di checksum per Codabar |
| [CodabarSymbol](./codabarsymbol) | Specifica il simbolo di inizio o fine della specifica del codice a barre Codabar. |
| [Code128Emulation](./code128emulation) | Parole in codice funzione per l'emulazione Code 128. Applicato solo per MicroPDF417. Ignorato per i codici a barre PDF417 e MacroPDF417. |
| [CodeLocation](./codelocation) | Posizione testo codice |
| [DataMatrixEccType](./datamatrixecctype) | Specificare il tipo di ECC da codificare. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Modalità di codifica dell'encoder DataMatrix, impostazione predefinita su Auto |
| [ECIEncodings](./eciencodings) | Identificatori di interpretazione del canale estesi. Viene utilizzato per comunicare al lettore di codici a barre i dettagli sui riferimenti utilizzati per la codifica dei dati nel simbolo. L'implementazione corrente consiste in tutte le codifiche di set di caratteri ben note. Attualmente viene utilizzato solo per codici a barre QR 2D. |
| [EnableChecksum](./enablechecksum) | Abilita checksum durante la generazione per codici a barre 1D. |
| [FontMode](./fontmode) | Modalità dimensione carattere. |
| [ITF14BorderType](./itf14bordertype) | ITF14 tipo di bordo del codice a barre |
| [MacroCharacter](./macrocharacter) | I valori dei caratteri 05 e 06 della macro vengono utilizzati per ottenere una codifica più compatta nelle modalità speciali. 05 Il cratere macro viene tradotto in "[)&gt;\u001E05\u001D" come intestazione dei dati decodificati e "\u001E\u0004" come trailer dei dati decodificati. 06 Macro craracter è tradotto in "[)&gt;\u001E06\u001D" come intestazione dati decodificata e "\u001E\u0004" come trailer dati decodificato. |
| [PatchFormat](./patchformat) | Formato PatchCode. Scegli PatchOnly per generare un singolo PatchCode. Usa il formato pagina per generare la pagina Patch con i PatchCode come bordi |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 modalità di compattazione codici a barre |
| [Pdf417ErrorLevel](./pdf417errorlevel) | pdf417 livello di correzione degli errori del codice a barre, dal livello 0 al livello 9, il livello 0 significa nessuna correzione degli errori, il livello 9 significa la migliore correzione degli errori |
| [QREncodeMode](./qrencodemode) | Modalità di codifica per codici a barre QR. Si consiglia di utilizzare Auto con CodeTextEncoding = Encoding.UTF8 per simboli o cifre latine e Utf8BOM per simboli Unicode. |
| [QREncodeType](./qrencodetype) | Modalità selettore QR / MicroQR. Selezionare ForceQR per i simboli QR standard, Auto per MicroQR. ForceMicroQR viene utilizzato per la generazione di simboli fortemente MicroQR, se possibile. |
| [QRErrorLevel](./qrerrorlevel) | Correzione dell'errore del livello di Reed-Solomon. Dal basso verso l'alto: LivelloL, LivelloM, LivelloQ, LivelloH. |
| [QRVersion](./qrversion) | Versione di QR Code. Da Version1 a Version40 per QR code e da M1 a M4 per MicroQr. |
| [TextAlignment](./textalignment) | Allineamento del testo. |
| [TwoDComponentType](./twodcomponenttype) | Tipo di componente 2D |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
