---
title: DataMatrixExtendedParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les données spéciales du code‑barres DataMatrix reconnu
type: docs
weight: 31
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Stocke les données spéciales du code‑barres DataMatrix reconnu

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur DataMatrixExtendedParameters spécifiée. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Obtient l'ID du code-barres en mode ajout structuré DataMatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Obtient le nombre de codes-barres en mode d'ajout structuré DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Obtient l'ID du code-barres en mode ajout structuré DataMatrix. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [isReaderProgramming()](#isReaderProgramming--) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Renvoie une valeur indiquant si la première valeur DataMatrixExtendedParameters est égale à la seconde. |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Renvoie une valeur indiquant si la première valeur DataMatrixExtendedParameters est différente de la seconde. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur DataMatrixExtendedParameters spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Obtient l'ID du code-barres en mode d'ajout structuré DataMatrix. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1.

Valeur : L'ID du code-barres en mode d'ajout structuré DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Obtient le nombre de codes-barres en mode d'ajout structuré DataMatrix. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

Valeur : Le nombre de codes-barres en mode d'ajout structuré DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Obtient l'ID du code-barres en mode d'ajout structuré DataMatrix. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1.

Valeur : L'ID du code-barres en mode d'ajout structuré DataMatrix.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Teste si tous les paramètres n'ont que des valeurs par défaut

Valeur : Renvoie  **true**  si tous les paramètres n'ont que des valeurs par défaut ; sinon,  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. La valeur par défaut est false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur DataMatrixExtendedParameters est égale à la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Une première valeur comparée |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a la même valeur que le second ; sinon,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur DataMatrixExtendedParameters est différente de la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Une première valeur comparée |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a une valeur différente du second ; sinon,  **false** .
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cet DataMatrixExtendedParameters.

**Returns:**
java.lang.String - Une chaîne qui représente ce DataMatrixExtendedParameters.
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

