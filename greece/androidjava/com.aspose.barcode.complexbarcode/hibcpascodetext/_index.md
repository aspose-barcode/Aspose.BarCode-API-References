---
title: HIBCPASCodetext
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS.
type: docs
weight: 18
url: /el/androidjava/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Adds new record |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Adds new record |
| [clear()](#clear--) | Clears records list |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  HIBCPASCodetext  value. |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί το codetext. |
| [getDataLocation()](#getDataLocation--) | Identifies data location. |
| [getRecords()](#getRecords--) | Gets records list |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί την παρουσία από το δημιουργημένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Λαμβάνει ή ορίζει τον τύπο του barcode. |
| [setDataLocation(int value)](#setDataLocation-int-) | Identifies data location. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


Adds new record

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Record to be added |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Adds new record

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| dataType | int | Type of data |
| data | java.lang.String | Data string |

### clear() {#clear--}
```
public void clear()
```


Clears records list

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  HIBCPASCodetext  value.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | An  HIBCPASCodetext  value to compare to this instance. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Λαμβάνει τον τύπο barcode.

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


Δημιουργεί το codetext.

**Returns:**
java.lang.String - Constructed codetext
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Identifies data location.

**Returns:**
int
### getRecords() {#getRecords--}
```
public List<HIBCPASRecord> getRecords()
```


Gets records list

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - List of records
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Αρχικοποιεί την παρουσία από το δημιουργημένο codetext.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

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


Gets or sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Identifies data location.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

