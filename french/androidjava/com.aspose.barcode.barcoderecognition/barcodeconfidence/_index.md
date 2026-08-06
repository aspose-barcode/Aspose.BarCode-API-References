---
title: BarCodeConfidence
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Contient le niveau de confiance de la reconnaissance
type: docs
weight: 13
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Contient le niveau de confiance de la reconnaissance

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## Champs

| Champ | Description |
| --- | --- |
| [MODERATE](#MODERATE) | Confiance de reconnaissance du code-barres (principalement les codes-barres 1D) avec une somme de contrôle faible ou même sans. |
| [NONE](#NONE) | Confiance de reconnaissance du code-barres lorsque le texte du code n'a pas été reconnu correctement ou que le code-barres a été détecté comme possible fakeBarCodeExtendedParameters. |
| [STRONG](#STRONG) | Confiance de reconnaissance qui a été confirmée avec des codes BCH comme Reed\\u2013Solomon. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


Confiance de reconnaissance du code-barres (principalement les codes-barres 1D) avec une somme de contrôle faible ou même sans. Peut contenir quelques erreurs de reconnaissance du texte ou même des reconnaissances factices si elle est basse.

### NONE {#NONE}
```
public static final int NONE
```


Confiance de reconnaissance du code-barres lorsque le texte du code n'a pas été reconnu correctement ou que le code-barres a été détecté comme possible fakeBarCodeExtendedParameters.

### STRONG {#STRONG}
```
public static final int STRONG
```


Confiance de reconnaissance confirmée par des codes BCH comme Reed\\u2013Solomon. Il ne doit pas y avoir d'erreurs dans le texte lu ou de reconnaissances factices.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

