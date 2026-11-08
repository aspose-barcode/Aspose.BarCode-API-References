---
title: "MaxiCodeStructuredCodetext"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3."
type: docs
weight: 31
url: /fr/java/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3. Cet exemple montre comment décoder le texte brut MaxiCode en instance de MaxiCodeStructuredCodetext.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) spécifiée. |
| [getBarcodeType()](#getBarcodeType--) | Obtient le type de code-barres. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construit le texte du code. |
| [getCountryCode()](#getCountryCode--) | Identifie le code pays à 3 chiffres. |
| [getECIEncoding()](#getECIEncoding--) | Obtient l'encodage ECI. |
| [getEncodeMode()](#getEncodeMode--) | Obtient un mode d'encodage MaxiCode. |
| [getMode()](#getMode--) | Obtient le mode MaxiCode. |
| [getPostalCode()](#getPostalCode--) | Identifie le code postal. |
| [getSecondMessage()](#getSecondMessage--) | Identifie le deuxième message du code-barres. |
| [getServiceCategory()](#getServiceCategory--) | Identifie la catégorie de service à 3 chiffres. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialise l'instance à partir du texte du code construit. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifie le code pays à 3 chiffres. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Définit l'encodage ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Définit un mode d'encodage MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) |  |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifie le deuxième message du code-barres. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifie la catégorie de service à 3 chiffres. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) à comparer à cette instance. |

**Returns:**
booléen -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
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
### getCountryCode() {#getCountryCode--}
```
public final int getCountryCode()
```


Identifie le code pays à 3 chiffres.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Obtient l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1

**Returns:**
int - encodage ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Obtient un mode d'encodage MaxiCode. Valeur par défaut: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract MaxiCodeMode getMode()
```


Obtient le mode MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 symboles alphanumériques en mode 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public final MaxiCodeSecondMessage getSecondMessage()
```


Identifie le deuxième message du code-barres.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public final int getServiceCategory()
```


Identifie la catégorie de service à 3 chiffres.

**Returns:**
int
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




### setCountryCode(int value) {#setCountryCode-int-}
```
public final void setCountryCode(int value)
```


Identifie le code pays à 3 chiffres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Définit l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est Auto. Valeur par défaut: ISO-8859-1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Encodage ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Définit un mode d'encodage MaxiCode. Valeur par défaut: Auto.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | un mode d'encodage MaxiCode. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public abstract void setPostalCode(String value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public final void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifie le deuxième message du code-barres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public final void setServiceCategory(int value)
```


Identifie la catégorie de service à 3 chiffres.

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
public final native void wait(long arg0)
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

