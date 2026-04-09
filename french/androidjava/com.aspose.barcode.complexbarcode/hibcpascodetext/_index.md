---
title: HIBCPASCodetext
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Classe pour encoder et décoder le texte intégré dans le code HIBC PAS.
type: docs
weight: 18
url: /fr/androidjava/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

Classe pour encoder et décoder le texte intégré dans le code HIBC PAS.

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Ajoute un nouvel enregistrement |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Ajoute un nouvel enregistrement |
| [clear()](#clear--) | Efface la liste des enregistrements |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur HIBCPASCodetext spécifiée. |
| [getBarcodeType()](#getBarcodeType--) | Obtient le type de code-barres. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construit le texte du code. |
| [getDataLocation()](#getDataLocation--) | Identifie l'emplacement des données. |
| [getRecords()](#getRecords--) | Obtient la liste des enregistrements |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialise l'instance à partir du texte du code construit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Obtient ou définit le type de code-barres. |
| [setDataLocation(int value)](#setDataLocation-int-) | Identifie l'emplacement des données. |
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


Ajoute un nouvel enregistrement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Enregistrement à ajouter |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Ajoute un nouvel enregistrement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataType | int | Type de données |
| data | java.lang.String | Chaîne de données |

### clear() {#clear--}
```
public void clear()
```


Efface la liste des enregistrements

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur HIBCPASCodetext spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur HIBCPASCodetext à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Obtient le type de code-barres.

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
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Identifie l'emplacement des données.

**Returns:**
int
### getRecords() {#getRecords--}
```
public List<HIBCPASRecord> getRecords()
```


Obtient la liste des enregistrements

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - Liste des enregistrements
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


Obtient ou définit le type de code-barres. Le codetext HIBC PAS peut être encodé en utilisant HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS et HIBCQRPAS. Valeur par défaut : HIBCCode39PAS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Identifie l'emplacement des données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

