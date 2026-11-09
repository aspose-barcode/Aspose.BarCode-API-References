---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode for Java API-referentie"
description: "BarcodeGenerator voor het genereren van backend barcode-afbeeldingen."
type: docs
weight: 13
url: /nl/java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator voor het genereren van backend barcode-afbeeldingen.

ondersteunde symbologieën: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Maakt een instantie van BarcodeGenerator aan. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Maakt een instantie van BarcodeGenerator aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | Maak alle gebruikte bronnen vrij. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exporteert BarCode‑eigenschappen naar de opgegeven xml‑stream |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genereer de barcode-afbeelding met de huidige instellingen. |
| [getBarcodeType()](#getBarcodeType--) | Barcode-symbologie type. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Te coderen tekst. |
| [getParameters()](#getParameters--) | Generatieparameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importeert BarCode-eigenschappen van de opgegeven xml-stream en maakt een BarcodeGenerator‑instantie aan. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importeert BarCode-eigenschappen van het opgegeven xml-bestand en maakt een BarcodeGenerator‑instantie aan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Sla de barcode-afbeelding op in een stream in een specifiek formaat. |
| [save(String filename)](#save-java.lang.String-) | Sla de barcode-afbeelding op in een specifiek bestand. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Sla de barcode-afbeelding op in een specifiek bestand in een specifiek formaat. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Barcode-symbologie type. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Stel codetext in als een reeks bytes. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Te coderen tekst. |
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


Maakt een instantie van BarcodeGenerator aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barcode-symbooltype. Gebruik de EncodeTypes‑klasse om een symbool in te stellen. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Maakt een instantie van BarcodeGenerator aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Barcode-symbooltype. Gebruik de EncodeTypes‑klasse om een symbool in te stellen. |
| codeText | java.lang.String | Te coderen tekst. |

### dispose() {#dispose--}
```
public void dispose()
```


Maak alle gebruikte bronnen vrij.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Exporteert BarCode‑eigenschappen naar de opgegeven xml‑stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xml | java.io.OutputStream | De xml-stream |

**Returns:**
boolean - Of de export al dan niet succesvol is voltooid. Retourneert **True** bij succes; **False** anders
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFile | java.lang.String | De naam van het bestand |

**Returns:**
boolean - Of de export al dan niet succesvol is voltooid.

Retourneert  **True**  in geval van succes;  **False**  anders
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Genereer de barcode-afbeelding met de huidige instellingen.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          BufferedImage image = generator.generateBarCodeImage();
>          ImageIO.write(image, "png",outputFile);
> ```

**Returns:**
java.awt.image.BufferedImage - Barcode-afbeelding. Zie  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Barcode-symbologie type.

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


Te coderen tekst.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Generatieparameters.

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


Importeert BarCode-eigenschappen van de opgegeven xml-stream en maakt een BarcodeGenerator‑instantie aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xml | java.io.InputStream | De xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importeert BarCode-eigenschappen van het opgegeven xml-bestand en maakt een BarcodeGenerator‑instantie aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlFile | java.lang.String | De naam van het bestand |

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


Sla de barcode-afbeelding op in een stream in een specifiek formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.OutputStream | Uitvoer OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specificeert het bestandsformaat van de uitvoerafbeelding. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Sla de barcode-afbeelding op in een specifiek bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | Pad om op te slaan. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Sla de barcode-afbeelding op in een specifiek bestand in een specifiek formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | Pad om op te slaan. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specificeert het bestandsformaat van de uitvoerafbeelding. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Barcode-symbologie type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Stel codetext in als een reeks bytes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeBytes | byte[] | Bytes van codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Te coderen tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt, voegt de functie automatisch een [byte order mark (BOM)][byte order mark _BOM] toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Het maakt handmatige codering van Unicode‑tekst mogelijk met nationale of speciale coderingen; deze methode wordt echter als verouderd beschouwd in moderne toepassingen. Voor moderne scenario's wordt [ECI][]‑codering aanbevolen voor Unicode‑gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode‑normen en kan leiden tot onvoorspelbare resultaten.

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
>  	Charset charset = Charset.forName("Shift_JIS");
>  	gen.setCodeText("\u8eca\u7a2e\u540d", charset);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(charset));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | java.lang.String | CodeText‑string |
| encoding | java.nio.charset.Charset | Toegepaste codering |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt en **insertBOM** is ingesteld op true, voegt de functie een [byte order mark (BOM)][byte order mark _BOM] toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Het maakt handmatige codering van Unicode‑tekst mogelijk met nationale of speciale coderingen; deze methode wordt echter als verouderd beschouwd in moderne toepassingen. Voor moderne scenario's wordt [ECI][]‑codering aanbevolen voor Unicode‑gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode‑normen en kan leiden tot onvoorspelbare resultaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | java.lang.String | CodeText‑string |
| encoding | java.nio.charset.Charset | Toegepaste codering |
| insertBOM | boolean | Geeft aan of een byte order mark (BOM) moet worden ingevoegd wanneer de opgegeven codering dit ondersteunt (bijv. UTF-8, UTF-16, UTF-32). Als ingesteld op true, wordt de BOM toegevoegd; als false, wordt de BOM weggelaten, zelfs als de codering normaal gesproken een BOM gebruikt. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

