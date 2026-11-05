---
title: "ChecksumValidation"
second_title: "Référence d'API Aspose.BarCode pour Android via Java"
description: 
type: docs
weight: 50
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/checksumvalidation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChecksumValidation extends Enum<ChecksumValidation>
```

Activez la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n’est possible que facultatif.

Checksum jamais utilisé : Codabar, PatchCode, Pharmacode, DataLogic2of5

Checksum possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum toujours utilisé : le reste des symbologies

--------------------

> ```
> This sample shows influence of ChecksumValidation on recognition quality and results
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  {
>      generator.save("c:\\test.png");
>  }
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13))
>  {
>      //checksum disabled
>      reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>          System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>      }
>  }
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  //checksum enabled
>  reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT](#DEFAULT) | Si le checksum est requis par la spécification - il sera validé. |
| [OFF](#OFF) | Ne pas valider le checksum. |
| [ON](#ON) | Validez toujours la somme de contrôle si possible. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DEFAULT {#DEFAULT}
```
public static final ChecksumValidation DEFAULT
```


Si le checksum est requis par la spécification - il sera validé.

### OFF {#OFF}
```
public static final ChecksumValidation OFF
```


Ne pas valider le checksum.

### ON {#ON}
```
public static final ChecksumValidation ON
```


Validez toujours la somme de contrôle si possible.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static ChecksumValidation fromValue(int value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChecksumValidation valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation)
### values() {#values--}
```
public static ChecksumValidation[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.ChecksumValidation[]
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

