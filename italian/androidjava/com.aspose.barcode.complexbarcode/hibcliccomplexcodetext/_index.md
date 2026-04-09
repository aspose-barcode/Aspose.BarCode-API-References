---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode per Android via Java API Reference
description: Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC.
type: docs
weight: 15
url: /it/androidjava/com.aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class HIBCLICComplexCodetext implements IComplexCodetext
```

Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC.

--------------------

> ```
> This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.HIBC_AZTEC_LIC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
>      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
>      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
>  }
> ```
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [HIBCLICComplexCodetext()](#HIBCLICComplexCodetext--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Ottiene o imposta il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisce il codetext. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza l'istanza dal codetext costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Ottiene o imposta il tipo di codice a barre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICComplexCodetext() {#HIBCLICComplexCodetext--}
```
public HIBCLICComplexCodetext()
```


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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Ottiene o imposta il tipo di codice a barre. Il codetext HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC tipi di codifica. Valore predefinito: HIBCCode39LIC.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public abstract String getConstructedCodetext()
```


Costruisce il codetext.

**Returns:**
java.lang.String - Codetext costruito
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
```


Inizializza l'istanza dal codetext costruito.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext costruito. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Ottiene o imposta il tipo di codice a barre. Il codetext HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC tipi di codifica. Valore predefinito: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

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

