---
title: DotCodeEncodeMode
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Mode d'encodage pour les codes-barres DotCode.
type: docs
weight: 85
url: /fr/androidjava/com.aspose.barcode.generation/dotcodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DotCodeEncodeMode extends Enum<DotCodeEncodeMode>
```

Mode d'encodage pour les codes-barres DotCode.

--------------------

> ```
> //Auto mode with macros
>  String codetext = ""[)>05CodetextWithMacros05"";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.save("test.bmp");
>  }
> 
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.bmp");
>  }
> 
>  //Bytes mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE);
>  {
>      generator.setCodetext(encodedArr);
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.BINARY);
>      generator.save("test.bmp");
>  }
>  //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Champs

| Champ | Description |
| --- | --- |
| [AUTO](#AUTO) | En mode Auto, le CodeText est encodé avec une compacité maximale des données. |
| [BINARY](#BINARY) | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. |
| [BYTES](#BYTES) | Encoder le texte de code en octets simples. |
| [ECI](#ECI) | En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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
### AUTO {#AUTO}
```
public static final DotCodeEncodeMode AUTO
```


En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré‑encodés dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée.

### BINARY {#BINARY}
```
public static final DotCodeEncodeMode BINARY
```


En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée.

### BYTES {#BYTES}
```
public static final DotCodeEncodeMode BYTES
```


Encoder le texte de code en octets simples. Si un caractère Unicode est détecté, le caractère sera encodé en deux octets, l’octet de poids faible en premier.

### ECI {#ECI}
```
public static final DotCodeEncodeMode ECI
```


En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée. Veuillez noter que certains scanners anciens (pré‑2006) peuvent ne pas prendre en charge ce mode.

### EXTENDED {#EXTENDED}
```
public static final DotCodeEncodeMode EXTENDED
```


Mode étendu qui prend en charge plusieurs modes ECI.

Il est préférable d'utiliser DotCodeExtCodetextBuilder pour la génération de texte codé étendu.

Utilisez la propriété Display2DText pour définir le texte visible en supprimant les caractères de gestion.

Les identifiants ECI sont définis comme une barre oblique unique et un identifiant à six chiffres "\\000026" - identifiant ECI UTF‑8.

Tous les caractères Unicode après l’identifiant ECI sont automatiquement encodés dans le jeu de caractères correct.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DotCodeEncodeMode EXTENDED_CODETEXT
```


Mode étendu qui prend en charge plusieurs modes ECI.

Il est préférable d'utiliser DotCodeExtCodetextBuilder pour la génération de texte codé étendu.

Utilisez la propriété Display2DText pour définir le texte visible en supprimant les caractères de gestion.

Les identifiants ECI sont définis comme une barre oblique unique et un identifiant à six chiffres "\\000026" - identifiant ECI UTF‑8.

Tous les caractères Unicode après l’identifiant ECI sont automatiquement encodés dans le jeu de caractères correct.

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
public static DotCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### values() {#values--}
```
public static DotCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DotCodeEncodeMode[]
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

