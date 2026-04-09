---
title: BarcodeGenerator
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: BarcodeGenerator for backend barcode images generation.
type: docs
weight: 13
url: /el/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator for backend barcode images generation.

υποστηριζόμενες συμβολές: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Δημιουργεί ένα αντικείμενο BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Δημιουργεί ένα αντικείμενο BarcodeGenerator. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-stream |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-file |
| [generateBarCodeImage()](#generateBarCodeImage--) | Δημιουργεί την εικόνα barcode σύμφωνα με τις τρέχουσες ρυθμίσεις. |
| [getBarcodeType()](#getBarcodeType--) | Τύπος συμβολής barcode. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Κείμενο προς κωδικοποίηση. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και δημιουργεί ένα αντικείμενο BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-file και δημιουργεί ένα αντικείμενο BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Αποθηκεύει το BarCodeImage σε ροή σε συγκεκριμένη μορφή. |
| [save(String filename)](#save-java.lang.String-) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Τύπος συμβολής barcode. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Ορίζει το codetext ως ακολουθία byte. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Κείμενο προς κωδικοποίηση. |
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


Δημιουργεί ένα αντικείμενο BarcodeGenerator.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Τύπος συμβολής barcode. Χρησιμοποιήστε την κλάση  EncodeTypes  για να ρυθμίσετε μια συμβολή. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Δημιουργεί ένα αντικείμενο BarcodeGenerator.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Τύπος συμβολής barcode. Χρησιμοποιήστε την κλάση  EncodeTypes  για να ρυθμίσετε μια συμβολή. |
| codeText | java.lang.String | Κείμενο προς κωδικοποίηση. |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-stream

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| xml | java.io.OutputStream | Το xml-stream |

**Returns:**
boolean - Εάν η εξαγωγή ολοκληρώθηκε επιτυχώς ή όχι. Επιστρέφει **True** σε περίπτωση επιτυχίας· **False** διαφορετικά
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-file

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Δημιουργεί την εικόνα barcode σύμφωνα με τις τρέχουσες ρυθμίσεις.

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


Τύπος συμβολής barcode.

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


Κείμενο προς κωδικοποίηση.

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


Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και δημιουργεί ένα αντικείμενο BarcodeGenerator.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| xml | java.io.InputStream | Το xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-file και δημιουργεί ένα αντικείμενο BarcodeGenerator.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

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


Αποθηκεύει το BarCodeImage σε ροή σε συγκεκριμένη μορφή.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Τύπος συμβολής barcode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Ορίζει το codetext ως ακολουθία byte.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codeBytes | byte[] | Bytes του codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Κείμενο προς κωδικοποίηση.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Κωδικοποιεί το Unicode **codeText** σε μια ακολουθία byte χρησιμοποιώντας το καθορισμένο **encoding**. Το UTF-8 είναι η πιο συχνά χρησιμοποιούμενη κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει, η συνάρτηση εισάγει αυτόματα ένα [byte order mark (BOM)][byte order mark _BOM].

Αυτή η λειτουργία προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει την χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη σε σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI][] για δεδομένα Unicode.

Η χρήση αυτής της λειτουργίας με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων 2D) ή HIBC barcode (συμπεριλαμβανομένων 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codeText | java.lang.String | Συμβολοσειρά CodeText |
| encoding | java.nio.charset.Charset | Εφαρμοσμένη κωδικοποίηση |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Κωδικοποιεί το Unicode **codeText** σε μια ακολουθία byte χρησιμοποιώντας το καθορισμένο **encoding**. Το UTF-8 είναι η πιο συχνά χρησιμοποιούμενη κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει και το **insertBOM** είναι ορισμένο σε true, η συνάρτηση περιλαμβάνει ένα [byte order mark (BOM)][byte order mark _BOM].

Αυτή η λειτουργία προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει την χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη σε σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI][] για δεδομένα Unicode.

Η χρήση αυτής της λειτουργίας με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων 2D) ή HIBC barcode (συμπεριλαμβανομένων 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| codeText | java.lang.String | Συμβολοσειρά CodeText |
| encoding | java.nio.charset.Charset | Εφαρμοσμένη κωδικοποίηση |
| insertBOM | boolean | Δείχνει εάν θα εισαχθεί ένα byte order mark (BOM) όταν η καθορισμένη κωδικοποίηση το υποστηρίζει (π.χ., UTF-8, UTF-16, UTF-32). Εάν οριστεί σε true, το BOM προστίθεται· εάν σε false, το BOM παραλείπεται ακόμη και αν η κωδικοποίηση το χρησιμοποιεί συνήθως. |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

