---
title: ComplexBarcodeGenerator
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: ComplexBarcodeGenerator pour le code-barres complexe du backend, ex.
type: docs
weight: 12
url: /fr/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator pour la génération d'images de code-barres complexes du backend (ex. SwissQR).

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Crée une instance de ComplexBarcodeGenerator. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose()](#dispose--) | Nettoie toutes les ressources utilisées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Génère une image de code-barres complexe selon les paramètres actuels. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Paramètres de génération. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Génère et enregistre une image de code-barres complexe selon les paramètres actuels. |
| [save(String filename)](#save-java.lang.String-) | Génère et enregistre une image de code-barres complexe selon les paramètres actuels. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Génère et enregistre une image de code-barres complexe selon les paramètres actuels. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Crée une instance de ComplexBarcodeGenerator.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Texte de code complexe |

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Génère une image de code-barres complexe selon les paramètres actuels.

**Returns:**
android.graphics.Bitmap - Image du code-barres. Voir  Bitmap .
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


Paramètres de génération.

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


Génère et enregistre une image de code-barres complexe selon les paramètres actuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | Sortie System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Spécifie le format de fichier de l'image de sortie. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Génère et enregistre une image de code-barres complexe selon les paramètres actuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Chemin où enregistrer. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Génère et enregistre une image de code-barres complexe selon les paramètres actuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom de fichier | java.lang.String | Chemin où enregistrer. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Spécifie le format de fichier de l'image de sortie. |

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

