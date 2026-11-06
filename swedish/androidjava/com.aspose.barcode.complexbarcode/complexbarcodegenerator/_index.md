---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "ComplexBarcodeGenerator för backend-komplex streckkod t.ex."
type: docs
weight: 12
url: /sv/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator för backend-komplex streckkod (t.ex. SwissQR) bildgenerering.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Skapar en instans av ComplexBarcodeGenerator. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose()](#dispose--) | Rensa upp eventuella resurser som används. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genererar komplex streckkodsbild med nuvarande inställningar. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Genereringsparametrar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Genererar och sparar komplex streckkodsbild med nuvarande inställningar. |
| [save(String filename)](#save-java.lang.String-) | Genererar och sparar komplex streckkodsbild med nuvarande inställningar. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Genererar och sparar komplex streckkodsbild med nuvarande inställningar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Skapar en instans av ComplexBarcodeGenerator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Komplex kodtext |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Genererar komplex streckkodsbild med nuvarande inställningar.

**Returns:**
android.graphics.Bitmap - Streckkod bild. Se  Bitmap .
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


Genereringsparametrar.

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


Genererar och sparar komplex streckkodsbild med nuvarande inställningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Utdata System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Anger filformatet för utdata bilden. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Genererar och sparar komplex streckkodsbild med nuvarande inställningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | Sökväg att spara till. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Genererar och sparar komplex streckkodsbild med nuvarande inställningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | Sökväg att spara till. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Anger filformatet för utdata bilden. |

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

