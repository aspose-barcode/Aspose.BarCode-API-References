---
title: AztecExtendedParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les données spéciales du code-barres Aztec reconnu
type: docs
weight: 12
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Stocke les données spéciales du code-barres Aztec reconnu

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended.getAztec.getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended.getAztec.getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended.getAztec.getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended.getAztec.isReaderInitialization());
>  }
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de  AztecExtendedParameters . |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Obtient l'ID du code-barres du mode d'ajout structuré Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Obtient le nombre de codes-barres du mode d'ajout structuré Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Obtient l'ID du fichier du mode d'ajout structuré Aztec. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [isReaderInitialization()](#isReaderInitialization--) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  AztecExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de  AztecExtendedParameters .

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


Obtient l'ID du code-barres du mode d'ajout structuré Aztec. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est 0.

Valeur: L'ID du code-barres du mode d'ajout structuré Aztec.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Obtient le nombre de codes-barres du mode d'ajout structuré Aztec. La valeur par défaut est 0. Le nombre doit être compris entre 1 et 26.

Valeur: Le nombre de codes-barres du mode d'ajout structuré Aztec.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Obtient l'ID du fichier du mode d'ajout structuré Aztec. La valeur par défaut est une chaîne vide

Valeur: L'ID du fichier du mode d'ajout structuré Aztec.

**Returns:**
java.lang.String
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
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
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




### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  AztecExtendedParameters .

**Returns:**
java.lang.String - Une chaîne qui représente ce  AztecExtendedParameters .
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

