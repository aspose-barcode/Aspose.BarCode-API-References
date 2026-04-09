---
title: HIBCLICCombinedCodetext
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour encoder et décoder le texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires.
type: docs
weight: 14
url: /fr/androidjava/com.aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICCombinedCodetext extends HIBCLICComplexCodetext
```

Classe pour encoder et décoder le texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires.

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICCombinedCodetext.
>  
> 
>  HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
>  combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  combinedCodetext.setPrimaryData(new PrimaryData());
>  combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
>  combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
>  combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
>  combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
>  combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
>  combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
>  combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
>  combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
>  BufferedImage image = generator.generateBarCodeImage();
>  BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>  reader.readBarCodes();
>  String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>  System.out.println("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
>  System.out.println("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
>  System.out.println("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
>  System.out.println("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
>  System.out.println("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
>  System.out.println("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
>  System.out.println("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
>  System.out.println("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HIBCLICCombinedCodetext()](#HIBCLICCombinedCodetext--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de  HIBCLICCombinedCodetext . |
| [getBarcodeType()](#getBarcodeType--) | Obtient ou définit le type de code-barres. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construit le texte du code. |
| [getPrimaryData()](#getPrimaryData--) | Identifie les données principales. |
| [getSecondaryAndAdditionalData()](#getSecondaryAndAdditionalData--) | Identifie les données secondaires et supplémentaires additionnelles. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialise l'instance à partir du texte du code construit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Obtient ou définit le type de code-barres. |
| [setPrimaryData(PrimaryData value)](#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-) | Identifie les données principales. |
| [setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)](#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | Identifie les données secondaires et supplémentaires additionnelles. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICCombinedCodetext() {#HIBCLICCombinedCodetext--}
```
public HIBCLICCombinedCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de  HIBCLICCombinedCodetext .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur  HIBCLICCombinedCodetext  à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Obtient ou définit le type de code-barres. Le texte de code HIBC LIC peut être encodé en utilisant les types d'encodage HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC et HIBCQRLIC. Valeur par défaut : HIBCCode39LIC.

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


Construit le texte du code.

**Returns:**
java.lang.String - Texte de code construit
### getPrimaryData() {#getPrimaryData--}
```
public PrimaryData getPrimaryData()
```


Identifie les données principales.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### getSecondaryAndAdditionalData() {#getSecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData getSecondaryAndAdditionalData()
```


Identifie les données secondaires et supplémentaires additionnelles.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialise l'instance à partir du texte du code construit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Texte de code construit. |

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


Obtient ou définit le type de code-barres. Le texte de code HIBC LIC peut être encodé en utilisant les types d'encodage HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC et HIBCQRLIC. Valeur par défaut : HIBCCode39LIC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setPrimaryData(PrimaryData value) {#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setPrimaryData(PrimaryData value)
```


Identifie les données principales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

### setSecondaryAndAdditionalData(SecondaryAndAdditionalData value) {#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)
```


Identifie les données secondaires et supplémentaires additionnelles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

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

