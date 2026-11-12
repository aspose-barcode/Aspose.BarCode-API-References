---
title: "DeconvolutionMode"
linktitle: "DeconvolutionMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità Deconvolution (restauro immagini) che definisce il livello di degradazione dell'immagine."
type: docs
weight: 220
url: /it/nodejs/global/deconvolutionmode/
---

## DeconvolutionMode

Modalità Deconvolution (restauro immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale come il blur, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che la corrompe, dobbiamo verificare le funzioni più conosciute come sharp o la morfologia matematica. Questo esempio mostra come utilizzare la modalità Deconvolution let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setDeconvolution(DeconvolutionMode.SLOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Valori

| Nome | Descrizione |
| --- | --- |
| ISO_8859_1 | ISO/IEC 8859-1 codifica alfabeto latino n. 1. ECI Id:"\000003" |
| ISO_8859_2 | ISO/IEC 8859-2 codifica alfabeto latino n. 2. ECI Id:"\000004" |
| ISO_8859_3 | ISO/IEC 8859-3 codifica alfabeto latino n. 3. ECI Id:"\000005" |
| ISO_8859_4 | ISO/IEC 8859-4 codifica alfabeto latino n. 4. ECI Id:"\000006" |
| ISO_8859_5 | ISO/IEC 8859-5 codifica alfabeto latino/cirillico. ECI Id:"\000007" |
| ISO_8859_6 | ISO/IEC 8859-6 codifica alfabeto latino/arabo. ECI Id:"\000008" |
| ISO_8859_7 | ISO/IEC 8859-7 codifica alfabeto latino/greco. ECI Id:"\000009" |
| ISO_8859_8 | ISO/IEC 8859-8 codifica alfabeto latino/ebraico. ECI Id:"\000010" |
| ISO_8859_9 | ISO/IEC 8859-9 codifica alfabeto latino n. 5. ECI Id:"\000011" |
| ISO_8859_10 | ISO/IEC 8859-10 codifica alfabeto latino n. 6. ECI Id:"\000012" |
| ISO_8859_11 | ISO/IEC 8859-11 codifica dell'alfabeto Latin/Thai. ECI Id:"\000013" |
| ISO_8859_13 | ISO/IEC 8859-13 codifica dell'alfabeto Latin No. 7 (Baltic Rim). ECI Id:"\000015" |
| ISO_8859_14 | ISO/IEC 8859-14 codifica dell'alfabeto Latin No. 8 (Celtic). ECI Id:"\000016" |
| ISO_8859_15 | ISO/IEC 8859-15 codifica dell'alfabeto Latin No. 9. ECI Id:"\000017" |
| ISO_8859_16 | ISO/IEC 8859-16 codifica dell'alfabeto Latin No. 10. ECI Id:"\000018" |
| Shift_JIS | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) codifica. ECI Id:"\000020" |
| Win1250 | Windows 1250 Latin 2 (Central Europe) codifica. ECI Id:"\000021" |
| Win1251 | Windows 1251 Cyrillic codifica. ECI Id:"\000022" |
| Win1252 | Windows 1252 Latin 1 codifica. ECI Id:"\000023" |
| Win1256 | Windows 1256 Arabic codifica. ECI Id:"\000024" |
| UTF16BE | ISO/IEC 10646 UCS-2 (High order byte first) codifica. ECI Id:"\000025" |
| UTF8 | ISO/IEC 10646 UTF-8 codifica. ECI Id:"\000026" |
| US_ASCII | ISO/IEC 646:1991 Versione di riferimento internazionale della codifica del set di caratteri a 7 bit ISO. ECI Id:"\000027" |
| Big5 | Big 5 (Taiwan) codifica del set di caratteri cinese. ECI Id:"\000028" |
| GB2312 | GB (RPC) codifica del set di caratteri cinese. ECI Id:"\000029" |
| EUC_KR | Codifica del set di caratteri coreano. ECI Id:"\000030" |
| GBK | GBK (estensione di GB2312 per il cinese semplificato) codifica. ECI Id:"\000031" |
| GB18030 | GGB18030 codifica del set di caratteri cinese. ECI Id:"\000032" |
| UTF16LE | Codifica ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | Codifica ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | Codifica ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | ISO/IEC 646: set di caratteri codificato a 7 bit ISO - codifica del set di caratteri invarianti. ECI Id:"\000170" |
| BINARY | Dati binari a 8 bit. ECI Id:"\000899" |
| NONE | Nessuna interpretazione estesa del canale |
