---
title: HIBCLICCombinedCodetext
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Codieren und Dekodieren des im HIBC LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert.
type: docs
weight: 14
url: /de/androidjava/com.aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICCombinedCodetext extends HIBCLICComplexCodetext
```

Klasse zum Codieren und Dekodieren des im HIBC LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert.

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
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [HIBCLICCombinedCodetext()](#HIBCLICCombinedCodetext--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  HIBCLICCombinedCodetext  Wert gleich ist. |
| [getBarcodeType()](#getBarcodeType--) | Liest oder setzt den Barcode‑Typ. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstellt Codetext. |
| [getPrimaryData()](#getPrimaryData--) | Identifiziert Primärdaten. |
| [getSecondaryAndAdditionalData()](#getSecondaryAndAdditionalData--) | Identifiziert sekundäre und zusätzliche ergänzende Daten. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Liest oder setzt den Barcode‑Typ. |
| [setPrimaryData(PrimaryData value)](#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-) | Identifiziert Primärdaten. |
| [setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)](#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | Identifiziert sekundäre und zusätzliche ergänzende Daten. |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  HIBCLICCombinedCodetext  Wert gleich ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein  HIBCLICCombinedCodetext  Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Liest oder setzt den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC.

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


Erstellt Codetext.

**Returns:**
java.lang.String – konstruierter Codetext
### getPrimaryData() {#getPrimaryData--}
```
public PrimaryData getPrimaryData()
```


Identifiziert Primärdaten.

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### getSecondaryAndAdditionalData() {#getSecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData getSecondaryAndAdditionalData()
```


Identifiziert sekundäre und zusätzliche ergänzende Daten.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialisiert die Instanz aus dem erstellten Codetext.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruiertes Codetext. |

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


Liest oder setzt den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setPrimaryData(PrimaryData value) {#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setPrimaryData(PrimaryData value)
```


Identifiziert Primärdaten.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

### setSecondaryAndAdditionalData(SecondaryAndAdditionalData value) {#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)
```


Identifiziert sekundäre und zusätzliche ergänzende Daten.

**Parameters:**
| Parameter | Type | Beschreibung |
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

