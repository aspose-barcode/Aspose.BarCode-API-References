---
title: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code die primaire gegevens opslaat."
type: docs
weight: 16
url: /nl/java/com.aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICPrimaryDataCodetext extends HIBCLICComplexCodetext
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code die primaire gegevens opslaat.

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HIBCLICPrimaryDataCodetext()](#HIBCLICPrimaryDataCodetext--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  HIBCLICPrimaryDataCodetext  waarde. |
| [getBarcodeType()](#getBarcodeType--) | Haalt of stelt het barcode-type in. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construeert codetext |
| [getData()](#getData--) | Identificeert primaire data. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Haalt of stelt het barcode-type in. |
| [setData(PrimaryData value)](#setData-com.aspose.barcode.complexbarcode.PrimaryData-) | Identificeert primaire data. |
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


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  HIBCLICPrimaryDataCodetext  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een  HIBCLICPrimaryDataCodetext  waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Haalt of stelt het barcode-type in. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC encodeertypen. Standaardwaarde: HIBCCode39LIC.

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


Construeert codetext

**Returns:**
java.lang.String - Gemaakt codetext
### getData() {#getData--}
```
public PrimaryData getData()
```


Identificeert primaire data.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialiseert instantie vanuit geconstrueerde codetext.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Gemaakt codetext. |

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


Haalt of stelt het barcode-type in. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC encodeertypen. Standaardwaarde: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(PrimaryData value) {#setData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setData(PrimaryData value)
```


Identificeert primaire data.

**Parameters:**
| Parameter | Type | Beschrijving |
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

