---
title: BarcodeGenerator
second_title: Aspose.BarCode per Android via Java API Reference
description: BarcodeGenerator per la generazione di immagini barcode lato backend.
type: docs
weight: 13
url: /it/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator per la generazione di immagini barcode lato backend.

simboli supportati: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Crea un'istanza di BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Crea un'istanza di BarcodeGenerator. |
## Methods

| Method | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Esporta le proprietà BarCode nello stream xml specificato |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Esporta le proprietà BarCode nel file xml specificato |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genera l'immagine del codice a barre con le impostazioni correnti. |
| [getBarcodeType()](#getBarcodeType--) | Tipo di simbologia del codice a barre. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Testo da codificare. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importa le proprietà BarCode dallo xml-stream specificato e crea un'istanza di BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importa le proprietà BarCode dal file XML specificato e crea un'istanza di BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Salva BarCodeImage nello stream in un formato specifico. |
| [save(String filename)](#save-java.lang.String-) | Salva l'immagine del codice a barre in un file specifico. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Salva l'immagine del codice a barre in un file specifico in un formato specifico. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Tipo di simbologia del codice a barre. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Imposta codetext come sequenza di byte. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Testo da codificare. |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) |  |
| [setCodeText(String codeText, Charset encoding, boolean insertBOM)](#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


Crea un'istanza di BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipo di simbologia del codice a barre. Usa la classe  EncodeTypes  per configurare una simbologia. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Crea un'istanza di BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipo di simbologia del codice a barre. Usa la classe  EncodeTypes  per configurare una simbologia. |
| codeText | java.lang.String | Testo da codificare. |

### dispose() {#dispose--}
```
public void dispose()
```


Clean up any resources being used.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Esporta le proprietà BarCode nello stream xml specificato

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| xml | java.io.OutputStream | Il xml-stream |

**Returns:**
boolean - Indica se l'esportazione è stata completata con successo o meno. Restituisce **True** in caso di successo; **False** altrimenti
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Esporta le proprietà BarCode nel file xml specificato

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| xmlFile | java.lang.String | Il nome del file |

**Returns:**
boolean - Indica se l'esportazione è stata completata con successo o meno.

Restituisce **True** in caso di successo; **False** altrimenti
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Genera l'immagine del codice a barre con le impostazioni correnti.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          OutputStream os = new FileOutputStream(outputFile);
>          Bitmap generatedBitmap = generator.generateBarCodeImage();
>          generatedBitmap.compress(Bitmap.CompressFormat.PNG, 100, os);
>          os.flush();
>          os.close();
> ```

**Returns:**
android.graphics.Bitmap - Barcode image. See  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Tipo di simbologia del codice a barre.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Testo da codificare.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Generation parameters.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


Importa le proprietà BarCode dallo xml-stream specificato e crea un'istanza di BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| xml | java.io.InputStream | Il xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importa le proprietà BarCode dal file XML specificato e crea un'istanza di BarcodeGenerator.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| xmlFile | java.lang.String | Il nome del file |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Salva BarCodeImage nello stream in un formato specifico.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Salva l'immagine del codice a barre in un file specifico.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome file | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Salva l'immagine del codice a barre in un file specifico in un formato specifico.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome file | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Tipo di simbologia del codice a barre.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Imposta codetext come sequenza di byte.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeBytes | byte[] | Byte di codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Testo da codificare.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Codifica il testo Unicode **codeText** in una sequenza di byte utilizzando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta, la funzione inserisce automaticamente un [byte order mark (BOM)][byte order mark _BOM].

Questa funzione è destinata all'uso esclusivo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale di testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per casi d'uso moderni, è consigliata la codifica [ECI][] per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codici a barre corrispondenti e può portare a risultati imprevedibili.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` setting Unicode-encoded text for 2D barcodes using different encodings:
>   
>   //Encode QR Code text using UTF-8 with BOM
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8;
>   gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode DataMatrix text using Shift-JIS (Japanese encoding)
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeText | java.lang.String | Stringa CodeText |
| codifica | java.nio.charset.Charset | Codifica applicata |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Codifica il testo Unicode **codeText** in una sequenza di byte utilizzando la **encoding** specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta e **insertBOM** è impostato su true, la funzione include un [byte order mark (BOM)][byte order mark _BOM].

Questa funzione è destinata all'uso esclusivo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale di testo Unicode utilizzando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per casi d'uso moderni, è consigliata la codifica [ECI][] per i dati Unicode.

L'utilizzo di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard di codici a barre corrispondenti e può portare a risultati imprevedibili.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` with or without a BOM for 2D barcodes.
>   
>  	//Encode codetext using UTF-8 with BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, true);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode codetext using UTF-8 without BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, false);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| codeText | java.lang.String | Stringa CodeText |
| codifica | java.nio.charset.Charset | Codifica applicata |
| insertBOM | boolean | Indica se inserire un byte order mark (BOM) quando la codifica specificata lo supporta (ad es., UTF-8, UTF-16, UTF-32). Se impostato su true, il BOM viene aggiunto; se false, il BOM viene omesso anche se la codifica normalmente ne prevede uno. |

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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

