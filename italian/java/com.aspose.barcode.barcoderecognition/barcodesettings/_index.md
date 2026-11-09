---
title: "BarcodeSettings"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "I principali parametri di decodifica del BarCode."
type: docs
weight: 19
url: /it/java/com.aspose.barcode.barcoderecognition/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

I principali parametri di decodifica del BarCode. Contiene parametri che influenzano i dati riconosciuti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustraliaPost()](#getAustraliaPost--) | Ottiene i parametri di decodifica AustraliaPost |
| [getChecksumValidation()](#getChecksumValidation--) | Abilita la convalida del checksum durante il riconoscimento per codici a barre 1D e postali. |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode. |
| [getStripFNC()](#getStripFNC--) | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. |
| [hashCode()](#hashCode--) |  |
| [isOnlyRequestedTypes()](#isOnlyRequestedTypes--) | Restituisce solo i tipi di codice a barre esplicitamente specificati per il riconoscimento. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumValidation(ChecksumValidation value)](#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-) | Abilita la convalida del checksum durante il riconoscimento per codici a barre 1D e postali. |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode. |
| [setOnlyRequestedTypes(boolean value)](#setOnlyRequestedTypes-boolean-) | Restituisce solo i tipi di codice a barre esplicitamente specificati per il riconoscimento. |
| [setStripFNC(boolean value)](#setStripFNC-boolean-) | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustraliaPost() {#getAustraliaPost--}
```
public AustraliaPostSettings getAustraliaPost()
```


Ottiene i parametri di decodifica AustraliaPost

**Returns:**
[AustraliaPostSettings](../../com.aspose.barcode.barcoderecognition/australiapostsettings) - The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology
### getChecksumValidation() {#getChecksumValidation--}
```
public ChecksumValidation getChecksumValidation()
```


Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo possibile. Checksum mai usato: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum sempre usato: Resto delle simbologie Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) - Enable checksum validation during recognition for 1D and Postal barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public boolean getDetectEncoding()
```


Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode. Il valore predefinito è true.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Valore: Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode

**Returns:**
boolean
### getStripFNC() {#getStripFNC--}
```
public boolean getStripFNC()
```


Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOnlyRequestedTypes() {#isOnlyRequestedTypes--}
```
public boolean isOnlyRequestedTypes()
```


Restituisce solo i tipi di codice a barre esplicitamente specificati per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false.

Esempio:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Returns:**
boolean - true se vengono restituiti solo i tipi di codice a barre richiesti esplicitamente; altrimenti false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumValidation(ChecksumValidation value) {#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-}
```
public void setChecksumValidation(ChecksumValidation value)
```


Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo possibile. Checksum mai usato: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum sempre usato: Resto delle simbologie Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) | Abilita la convalida del checksum durante il riconoscimento per codici a barre 1D e postali. |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public void setDetectEncoding(boolean value)
```


Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode. Il valore predefinito è true.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Valore: Il flag che forza il motore a rilevare la codifica del testo del codice per set di caratteri Unicode

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setOnlyRequestedTypes(boolean value) {#setOnlyRequestedTypes-boolean-}
```
public void setOnlyRequestedTypes(boolean value)
```


Restituisce solo i tipi di codice a barre esplicitamente specificati per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false.

Esempio:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes())
 {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStripFNC(boolean value) {#setStripFNC-boolean-}
```
public void setStripFNC(boolean value)
```


Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. Esempio BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

