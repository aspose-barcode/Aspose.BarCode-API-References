---
title: ComplexBarcodeGenerator
second_title: Aspose.BarCode für Android via Java API-Referenz
description: ComplexBarcodeGenerator für komplexe Backend-Barcodes z. B.
type: docs
weight: 12
url: /de/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator zur Erzeugung von Bildern komplexer Backend-Barcodes (z. B. SwissQR).

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Erstellt eine Instanz von ComplexBarcodeGenerator. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [dispose()](#dispose--) | Räumt alle verwendeten Ressourcen auf. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Erzeugt ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Erzeugungsparameter. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [save(String filename)](#save-java.lang.String-) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Erstellt eine Instanz von ComplexBarcodeGenerator.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Komplexer Codetext |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Erzeugt ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

**Returns:**
android.graphics.Bitmap - Barcode-Bild. Siehe Bitmap.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Erzeugungsparameter.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Ausgabe System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Gibt das Dateiformat des Ausgabebildes an. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Pfad zum Speichern. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Pfad zum Speichern. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Gibt das Dateiformat des Ausgabebildes an. |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

