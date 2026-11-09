---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode för Java API-referens"
description: "BarcodeGenerator för generering av streckkodsbilder i backend."
type: docs
weight: 13
url: /sv/java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator för generering av streckkodsbilder i backend.

stödda symbologier: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Skapar en instans av BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Skapar en instans av BarcodeGenerator. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose()](#dispose--) | Rensa upp eventuella resurser som används. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exporterar BarCode‑egenskaper till den angivna xml‑strömmen |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exporterar BarCode‑egenskaper till den angivna xml‑filen |
| [generateBarCodeImage()](#generateBarCodeImage--) | Generera streckkodbilden med aktuella inställningar. |
| [getBarcodeType()](#getBarcodeType--) | Typ av streckkodssymbologi. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Text att koda. |
| [getParameters()](#getParameters--) | Genereringsparametrar. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importerar BarCode-egenskaper från den angivna xml-streamen och skapar BarcodeGenerator-instans. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importerar BarCode-egenskaper från den angivna xml-filen och skapar BarcodeGenerator-instans. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Spara streckkodbild till ström i specifikt format. |
| [save(String filename)](#save-java.lang.String-) | Spara streckkodbild till specifik fil. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Spara streckkodbild till specifik fil i specifikt format. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Typ av streckkodssymbologi. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Ange codetext som en sekvens av byte. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Text att koda. |
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


Skapar en instans av BarcodeGenerator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Streckkodssymbologityp. Använd EncodeTypes-klassen för att konfigurera en symbologi. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Skapar en instans av BarcodeGenerator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Streckkodssymbologityp. Använd EncodeTypes-klassen för att konfigurera en symbologi. |
| codeText | java.lang.String | Text att koda. |

### dispose() {#dispose--}
```
public void dispose()
```


Rensa upp eventuella resurser som används.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Exporterar BarCode‑egenskaper till den angivna xml‑strömmen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xml | java.io.OutputStream | Den xml-streamen |

**Returns:**
boolean - Om exporten slutfördes framgångsrikt eller inte. Returnerar **True** vid framgång; **False** annars
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exporterar BarCode‑egenskaper till den angivna xml‑filen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | java.lang.String | Filens namn |

**Returns:**
boolean - Huruvida exporten slutfördes framgångsrikt eller inte.

Returnerar  **True**  vid framgång;  **False**  annars
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Generera streckkodbilden med aktuella inställningar.

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
java.awt.image.BufferedImage - Streckkodbild. Se  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Typ av streckkodssymbologi.

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


Text att koda.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Genereringsparametrar.

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


Importerar BarCode-egenskaper från den angivna xml-streamen och skapar BarcodeGenerator-instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xml | java.io.InputStream | Den xml-streamen |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importerar BarCode-egenskaper från den angivna xml-filen och skapar BarcodeGenerator-instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFile | java.lang.String | Filens namn |

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


Spara streckkodbild till ström i specifikt format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Utdata OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Anger filformatet för utdata bilden. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Spara streckkodbild till specifik fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | java.lang.String | Sökväg att spara till. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Spara streckkodbild till specifik fil i specifikt format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filnamn | java.lang.String | Sökväg att spara till. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Anger filformatet för utdata bilden. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Typ av streckkodssymbologi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Ange codetext som en sekvens av byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeBytes | byte[] | Byte av codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Text att koda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Kodar Unicode **codeText** till en bytesekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stöder det, infogar funktionen automatiskt ett [byte order mark (BOM)][byte order mark _BOM].

Denna funktion är avsedd att endast användas med 2D-streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR osv.). Den möjliggör manuell kodning av Unicode‑text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI][]‑kodning för Unicode‑data.

Att använda denna funktion med 1D-streckkoder, GS1‑kompatibla streckkoder (inklusive 2D) eller HIBC‑streckkoder (inklusive 2D) stöds inte av motsvarande streckkodstandarder och kan leda till oförutsägbara resultat.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | java.lang.String | CodeText sträng |
| kodning | java.nio.charset.Charset | Tillämad kodning |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Kodar Unicode **codeText** till en bytesekvens med den angivna **encoding**. UTF-8 är den mest använda kodningen. Om kodningen stöder det och **insertBOM** är satt till true, inkluderar funktionen ett [byte order mark (BOM)][byte order mark _BOM].

Denna funktion är avsedd att endast användas med 2D-streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR osv.). Den möjliggör manuell kodning av Unicode‑text med nationella eller speciella kodningar; dock anses denna metod vara föråldrad i moderna applikationer. För moderna användningsfall rekommenderas [ECI][]‑kodning för Unicode‑data.

Att använda denna funktion med 1D-streckkoder, GS1‑kompatibla streckkoder (inklusive 2D) eller HIBC‑streckkoder (inklusive 2D) stöds inte av motsvarande streckkodstandarder och kan leda till oförutsägbara resultat.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codeText | java.lang.String | CodeText sträng |
| kodning | java.nio.charset.Charset | Tillämad kodning |
| insertBOM | boolean | Anger om ett byte order mark (BOM) ska infogas när den angivna kodningen stöder det (t.ex. UTF-8, UTF-16, UTF-32). Om satt till true läggs BOM till; om false utelämnas BOM även om kodningen normalt använder ett. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

