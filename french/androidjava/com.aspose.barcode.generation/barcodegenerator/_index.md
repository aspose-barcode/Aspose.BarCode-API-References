---
title: BarcodeGenerator
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: BarcodeGenerator pour la génération d'images de codes-barres côté serveur.
type: docs
weight: 13
url: /fr/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator pour la génération d'images de codes-barres côté serveur.

symbologies prises en charge : 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Crée une instance de BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Crée une instance de BarcodeGenerator. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose()](#dispose--) | Nettoie toutes les ressources utilisées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Exporte les propriétés BarCode vers le flux xml spécifié |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Exporte les propriétés BarCode vers le fichier xml spécifié |
| [generateBarCodeImage()](#generateBarCodeImage--) | Génère l'image du code-barres avec les paramètres actuels. |
| [getBarcodeType()](#getBarcodeType--) | Type de symbologie du code-barres. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Texte à encoder. |
| [getParameters()](#getParameters--) | Paramètres de génération. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Importe les propriétés BarCode depuis le flux XML spécifié et crée une instance de BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importe les propriétés BarCode depuis le fichier XML spécifié et crée une instance de BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Enregistre BarCodeImage dans le flux dans un format spécifique. |
| [save(String filename)](#save-java.lang.String-) | Enregistre l'image du code-barres dans un fichier spécifique. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Type de symbologie du code-barres. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Définit le texte du code comme une séquence d'octets. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Texte à encoder. |
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


Crée une instance de BarcodeGenerator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Type de symbologie du code-barres. Utilisez la classe  EncodeTypes  pour configurer une symbologie. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Crée une instance de BarcodeGenerator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Type de symbologie du code-barres. Utilisez la classe  EncodeTypes  pour configurer une symbologie. |
| codeText | java.lang.String | Texte à encoder. |

### dispose() {#dispose--}
```
public void dispose()
```


Nettoie toutes les ressources utilisées.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Exporte les propriétés BarCode vers le flux xml spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xml | java.io.OutputStream | Le xml-stream |

**Returns:**
booléen - Indique si l'exportation s'est terminée avec succès ou non. Retourne **True** en cas de succès ; **False** sinon
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Exporte les propriétés BarCode vers le fichier xml spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | Le nom du fichier |

**Returns:**
booléen - Indique si l'exportation s'est terminée avec succès ou non.

Renvoie  **True**  en cas de succès ;  **False**  sinon
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Génère l'image du code-barres avec les paramètres actuels.

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
android.graphics.Bitmap - Image du code-barres. Voir  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Type de symbologie du code-barres.

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


Texte à encoder.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Paramètres de génération.

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


Importe les propriétés BarCode depuis le flux XML spécifié et crée une instance de BarcodeGenerator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xml | java.io.InputStream | Le xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Importe les propriétés BarCode depuis le fichier XML spécifié et crée une instance de BarcodeGenerator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | Le nom du fichier |

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


Enregistre BarCodeImage dans le flux dans un format spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Enregistre l'image du code-barres dans un fichier spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Chemin où enregistrer. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Chemin où enregistrer. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Spécifie le format de fichier de l'image de sortie. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Type de symbologie du code-barres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Définit le texte du code comme une séquence d'octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| codeBytes | byte[] | Octets du codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Texte à encoder.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge, la fonction insère automatiquement un [byte order mark (BOM)][byte order mark _BOM].

Cette fonction est destinée à être utilisée uniquement avec les codes-barres 2D (p. ex., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Elle permet l'encodage manuel du texte Unicode en utilisant des encodages nationaux ou spéciaux ; cependant, cette méthode est considérée comme obsolète dans les applications modernes. Pour les cas d'utilisation modernes, l'encodage [ECI][] est recommandé pour les données Unicode.

L'utilisation de cette fonction avec des codes-barres 1D, des codes-barres conformes à GS1 (y compris 2D), ou des codes-barres HIBC (y compris 2D) n'est pas prise en charge par les normes de codes-barres correspondantes et peut entraîner des résultats imprévisibles.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | Chaîne CodeText |
| encodage | java.nio.charset.Charset | Encodage appliqué |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge et que **insertBOM** est défini sur true, la fonction inclut un [byte order mark (BOM)][byte order mark _BOM].

Cette fonction est destinée à être utilisée uniquement avec les codes-barres 2D (p. ex., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Elle permet l'encodage manuel du texte Unicode en utilisant des encodages nationaux ou spéciaux ; cependant, cette méthode est considérée comme obsolète dans les applications modernes. Pour les cas d'utilisation modernes, l'encodage [ECI][] est recommandé pour les données Unicode.

L'utilisation de cette fonction avec des codes-barres 1D, des codes-barres conformes à GS1 (y compris 2D), ou des codes-barres HIBC (y compris 2D) n'est pas prise en charge par les normes de codes-barres correspondantes et peut entraîner des résultats imprévisibles.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | Chaîne CodeText |
| encodage | java.nio.charset.Charset | Encodage appliqué |
| insertBOM | boolean | Indique s'il faut insérer un marqueur d'ordre d'octet (BOM) lorsque l'encodage spécifié le prend en charge (p. ex., UTF-8, UTF-16, UTF-32). Si défini sur true, le BOM est ajouté ; si false, le BOM est omis même si l'encodage en utilise normalement un. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

