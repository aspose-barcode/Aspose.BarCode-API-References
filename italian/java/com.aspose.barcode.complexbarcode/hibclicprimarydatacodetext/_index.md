---
title: "HIBCLICPrimaryDataCodetext"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari."
type: docs
weight: 16
url: /it/java/com.aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICPrimaryDataCodetext extends HIBCLICComplexCodetext
```

Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICPrimaryDataCodetext.
>  
>  HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
>  complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  complexCodetext.setData(new PrimaryData());
>  complexCodetext.getData().setProductOrCatalogNumber("12345");
>  complexCodetext.getData().setLabelerIdentificationCode("A999");
>  complexCodetext.getData().setUnitOfMeasureID(1);
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>  {
>      BufferedImage image = generator.generateBarCodeImage();
>      BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>      {
>          reader.readBarCodes();
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
>          HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>          System.out.println("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
>          System.out.println("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
>          System.out.println("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
>      }
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HIBCLICPrimaryDataCodetext()](#HIBCLICPrimaryDataCodetext--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  HIBCLICPrimaryDataCodetext  specificato. |
| [getBarcodeType()](#getBarcodeType--) | Ottiene o imposta il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisce il testo del codice. |
| [getData()](#getData--) | Identifica i dati primari. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza l'istanza dal testo del codice costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Ottiene o imposta il tipo di codice a barre. |
| [setData(PrimaryData value)](#setData-com.aspose.barcode.complexbarcode.PrimaryData-) | Identifica i dati primari. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICPrimaryDataCodetext() {#HIBCLICPrimaryDataCodetext--}
```
public HIBCLICPrimaryDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore  HIBCLICPrimaryDataCodetext  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore  HIBCLICPrimaryDataCodetext  da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Ottiene o imposta il tipo di codice a barre. Il testo del codice HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC.

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
public String getConstructedCodetext()
```


Costruisce il testo del codice.

**Returns:**
java.lang.String - Testo codificato costruito
### getData() {#getData--}
```
public PrimaryData getData()
```


Identifica i dati primari.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inizializza l'istanza dal testo del codice costruito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Testo codificato costruito. |

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


Ottiene o imposta il tipo di codice a barre. Il testo del codice HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(PrimaryData value) {#setData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setData(PrimaryData value)
```


Identifica i dati primari.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

