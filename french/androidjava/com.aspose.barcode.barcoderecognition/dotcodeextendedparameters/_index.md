---
title: DotCodeExtendedParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les données spéciales du code‑barres DotCode reconnu
type: docs
weight: 33
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Stocke les données spéciales du code‑barres DotCode reconnu

Cet exemple montre comment obtenir les valeurs brutes de DotCode

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) spécifiée. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Obtient l'ID du code-barres DotCode en mode d'ajout structuré. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Obtient le nombre de code-barres DotCode en mode d'ajout structuré. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Obtient l'ID du code-barres DotCode en mode d'ajout structuré. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Obtient le nombre de code-barres DotCode en mode d'ajout structuré. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [isReaderInitialization()](#isReaderInitialization--) | Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Renvoie une valeur indiquant si la première valeur de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) est égale à la seconde. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Renvoie une valeur indiquant si la première valeur de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) est différente de la seconde. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) spécifiée.

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
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


Indique si le code est utilisé pour demander au lecteur d’interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres. La valeur par défaut est false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Obtient l'ID du code-barres DotCode en mode d'ajout structuré. L'ID commence à 1 et doit être inférieur ou égal au nombre de code-barres. La valeur par défaut est -1.

Valeur : L'ID du code-barres DotCode en mode d'ajout structuré.

**Returns:**
int - l'ID du code-barres DotCode en mode d'ajout structuré.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Obtient le nombre de code-barres DotCode en mode d'ajout structuré. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

Valeur : Le nombre de code-barres DotCode en mode d'ajout structuré.

**Returns:**
int - le nombre de code-barres DotCode en mode d'ajout structuré.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Obtient l'ID du code-barres DotCode en mode d'ajout structuré. L'ID commence à 1 et doit être inférieur ou égal au nombre de code-barres. La valeur par défaut est -1.

Valeur : L'ID du code-barres DotCode en mode d'ajout structuré.

**Returns:**
int - l'ID du code-barres DotCode en mode d'ajout structuré.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Obtient le nombre de code-barres DotCode en mode d'ajout structuré. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35.

Valeur : Le nombre de code-barres DotCode en mode d'ajout structuré.

**Returns:**
int - le nombre de code-barres DotCode en mode d'ajout structuré.
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
public final boolean isReaderInitialization()
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




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) est égale à la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Une première valeur comparée |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a la même valeur que le second ; sinon,  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Renvoie une valeur indiquant si la première valeur de [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) est différente de la seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Une première valeur comparée |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Une seconde valeur comparée |

**Returns:**
boolean -  **true**  si le premier a une valeur différente du second ; sinon,  **false** .
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de cet [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Une chaîne qui représente cet [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

