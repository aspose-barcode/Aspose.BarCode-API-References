---
title: BarCodeResult
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke les données du code-barres reconnu comme SingleDecodeType type string codetext BarCodeRegionParameters region et d'autres paramètres
type: docs
weight: 18
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Stocke les données du code-barres reconnu comme le type SingleDecodeType, la chaîne codetext, les paramètres BarCodeRegionParameters region et d'autres paramètres

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Crée une copie de la classe BarCodeResult. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie de la classe BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeResult spécifiée. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Obtient les octets du code encodés |
| [getCodeText()](#getCodeText--) | Obtient le texte du code |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | Obtient le texte du code avec encodage. |
| [getCodeType()](#getCodeType--) | Obtient le type de code-barres |
| [getCodeTypeName()](#getCodeTypeName--) | Obtient le nom du type de code-barres |
| [getConfidence()](#getConfidence--) | Obtient le niveau de confiance de reconnaissance du code-barres reconnu |
| [getExtended()](#getExtended--) | Obtient les paramètres étendus du code-barres reconnu |
| [getReadingQuality()](#getReadingQuality--) | Obtient la qualité de lecture. |
| [getRegion()](#getRegion--) | Obtient la région du code-barres |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Crée une copie de la classe BarCodeResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Une copie de l'instance BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie de la classe BarCodeResult.

**Returns:**
java.lang.Object - Renvoie une copie de la classe BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeResult spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur BarCodeResult à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Obtient les octets du code encodés

Valeur : Les octets du code du code-barres

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Obtient le texte du code

Valeur : Le texte du code-barres

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


Obtient le texte du code avec encodage.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodage | java.nio.charset.Charset | L'encodage pour le texte du code. |

**Returns:**
java.lang.String - Une chaîne contenant le texte du code reconnu.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Obtient le type de code-barres

Valeur : Les informations de type du code-barres reconnu

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Obtient le nom du type de code-barres

Valeur : Le nom du type du code-barres reconnu

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


Obtient le niveau de confiance de reconnaissance du code-barres reconnu

Valeur :  BarCodeConfidence.Strong  ne présente pas de faux ou de mauvaises reconnaissances,  BarCodeConfidence.Moderate  peut parfois contenir des faux ou un texte de code incorrect car ce niveau de confiance concerne les codes-barres avec un checksum faible ou même sans,  BarCodeConfidence.None  a toujours un texte de code incorrect et peut être des reconnaissances factices

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Obtient les paramètres étendus du code-barres reconnu

Valeur : Les paramètres étendus du code-barres reconnu

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Obtient la qualité de lecture. Fonctionne pour les codes-barres 1D et postaux.

Valeur : Le pourcentage de qualité de lecture

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Obtient la région du code-barres

Valeur : La région du code-barres reconnu

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
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


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce BarCodeResult.

**Returns:**
java.lang.String - Une chaîne qui représente ce  BarCodeResult .
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

