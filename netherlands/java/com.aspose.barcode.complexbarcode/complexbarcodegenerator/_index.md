---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Java API-referentie"
description: "ComplexBarcodeGenerator voor backend complexe barcode bijv."
type: docs
weight: 12
url: /nl/java/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator voor backend complexe barcode (bijv. SwissQR) afbeeldingengeneratie.

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

| Constructor | Beschrijving |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Maakt een instantie van ComplexBarcodeGenerator aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | Maak alle gebruikte bronnen vrij. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genereert een complexe barcode-afbeelding volgens de huidige instellingen. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Generatieparameters. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen. |
| [save(String filename)](#save-java.lang.String-) | Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Maakt een instantie van ComplexBarcodeGenerator aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Complexe codetekst |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Genereert een complexe barcode-afbeelding volgens de huidige instellingen.

**Returns:**
java.awt.image.BufferedImage - Barcode-afbeelding. Zie  Bitmap .
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


Generatieparameters.

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


Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | java.io.OutputStream | Uitvoer System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specificeert het bestandsformaat van de uitvoerafbeelding. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | Pad om op te slaan. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Genereert en slaat een complexe barcode-afbeelding op volgens de huidige instellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | Pad om op te slaan. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specificeert het bestandsformaat van de uitvoerafbeelding. |

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

