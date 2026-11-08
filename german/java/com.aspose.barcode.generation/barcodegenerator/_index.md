---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "BarcodeGenerator zur Erzeugung von Backend-Barcode-Bildern."
type: docs
weight: 13
url: /de/java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator zur Erzeugung von Backend-Barcode-Bildern.

unterstützte Symbologien: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR-Code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Erstellt eine Instanz von BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Erstellt eine Instanz von BarcodeGenerator. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [dispose()](#dispose--) | Räumt alle verwendeten Ressourcen auf. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exportiert BarCode‑Eigenschaften in den angegebenen XML‑Stream |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exportiert BarCode‑Eigenschaften in die angegebene XML‑Datei |
| [generateBarCodeImage()](#generateBarCodeImage--) | Erzeugt das Strichcode‑Bild mit den aktuellen Einstellungen. |
| [getBarcodeType()](#getBarcodeType--) | Strichcode‑Symbologie‑Typ. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Zu codierender Text. |
| [getParameters()](#getParameters--) | Generierungsparameter. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importiert BarCode‑Eigenschaften aus dem angegebenen XML‑Stream und erstellt eine BarcodeGenerator‑Instanz. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und erstellt eine BarcodeGenerator‑Instanz. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Speichert das Strichcode‑Bild in einen Stream in einem bestimmten Format. |
| [save(String filename)](#save-java.lang.String-) | Speichert das Strichcode‑Bild in einer bestimmten Datei. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Speichert das Strichcode‑Bild in einer bestimmten Datei in einem bestimmten Format. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Strichcode‑Symbologie‑Typ. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Setzt den Codetext als Byte‑Sequenz. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Zu codierender Text. |
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


Erstellt eine Instanz von BarcodeGenerator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Strichcode‑Symbologie‑Typ. Verwenden Sie die EncodeTypes‑Klasse, um eine Symbologie einzurichten. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Erstellt eine Instanz von BarcodeGenerator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Strichcode‑Symbologie‑Typ. Verwenden Sie die EncodeTypes‑Klasse, um eine Symbologie einzurichten. |
| codeText | java.lang.String | Zu codierender Text. |

### dispose() {#dispose--}
```
public void dispose()
```


Räumt alle verwendeten Ressourcen auf.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Exportiert BarCode‑Eigenschaften in den angegebenen XML‑Stream

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xml | java.io.OutputStream | Der xml-stream |

**Returns:**
boolean - Ob der Export erfolgreich abgeschlossen wurde. Gibt **True** im Erfolgsfall zurück; **False** sonst
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exportiert BarCode‑Eigenschaften in die angegebene XML‑Datei

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFile | java.lang.String | Der Name der Datei |

**Returns:**
boolean – Ob der Export erfolgreich abgeschlossen wurde oder nicht.

Gibt **True** im Erfolgsfall zurück; **False** sonst
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Erzeugt das Strichcode‑Bild mit den aktuellen Einstellungen.

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
java.awt.image.BufferedImage - Barcode-Bild. Siehe Bitmap.
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Strichcode‑Symbologie‑Typ.

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


Zu codierender Text.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Generierungsparameter.

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


Importiert BarCode‑Eigenschaften aus dem angegebenen XML‑Stream und erstellt eine BarcodeGenerator‑Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xml | java.io.InputStream | Der xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und erstellt eine BarcodeGenerator‑Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFile | java.lang.String | Der Name der Datei |

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


Speichert das Strichcode‑Bild in einen Stream in einem bestimmten Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Ausgabe OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Gibt das Dateiformat des Ausgabebildes an. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Speichert das Strichcode‑Bild in einer bestimmten Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Pfad zum Speichern. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Speichert das Strichcode‑Bild in einer bestimmten Datei in einem bestimmten Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Pfad zum Speichern. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Gibt das Dateiformat des Ausgabebildes an. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Strichcode‑Symbologie‑Typ.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Setzt den Codetext als Byte‑Sequenz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeBytes | byte[] | Bytes des codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Zu codierender Text.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Kodiert den Unicode **codeText** in eine Bytefolge unter Verwendung der angegebenen **encoding**. UTF-8 ist die am häufigsten verwendete Kodierung. Unterstützt die Kodierung dies, fügt die Funktion automatisch ein [byte order mark (BOM)][byte order mark _BOM] ein.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes gedacht (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für moderne Anwendungsfälle wird die [ECI][]‑Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den entsprechenden Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | java.lang.String | CodeText‑Zeichenfolge |
| Kodierung | java.nio.charset.Charset | Verwendete Kodierung |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Kodiert den Unicode **codeText** in eine Bytefolge unter Verwendung der angegebenen **encoding**. UTF-8 ist die am häufigsten verwendete Kodierung. Unterstützt die Kodierung dies und ist **insertBOM** auf true gesetzt, fügt die Funktion ein [byte order mark (BOM)][byte order mark _BOM] ein.

Diese Funktion ist ausschließlich für die Verwendung mit 2D‑Barcodes gedacht (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode‑Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für moderne Anwendungsfälle wird die [ECI][]‑Kodierung für Unicode‑Daten empfohlen.

Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den entsprechenden Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| codeText | java.lang.String | CodeText‑Zeichenfolge |
| Kodierung | java.nio.charset.Charset | Verwendete Kodierung |
| insertBOM | boolesch | Gibt an, ob ein Byte Order Mark (BOM) eingefügt werden soll, wenn die angegebene Kodierung dies unterstützt (z. B. UTF-8, UTF-16, UTF-32). Ist sie auf true gesetzt, wird das BOM hinzugefügt; ist sie auf false gesetzt, wird das BOM weggelassen, selbst wenn die Kodierung normalerweise eines verwendet. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

