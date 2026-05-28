---
title: DataMatrixEncodeMode
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Le mode d’encodage des encodeurs DataMatrix est par défaut sur Auto.
type: docs
weight: 83
url: /fr/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Mode d'encodage de l'encodeur DataMatrix, par défaut sur Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Champs

| Champ | Description |
| --- | --- |
| [ANSIX12](#ANSIX12) | Utilise l’encodage ANSI X12. |
| [ASCII](#ASCII) | Encode un caractère alphanumérique ou deux caractères numériques par octet. |
| [AUTO](#AUTO) | En mode Auto, le CodeText est encodé avec une compacité maximale des données. |
| [BASE_256](#BASE-256) | Encode des valeurs 8 bits. |
| [BINARY](#BINARY) | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. |
| [BYTES](#BYTES) | Encode des valeurs 8 bits. |
| [C40](#C40) | Utilise l’encodage C40. |
| [ECI](#ECI) | En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. |
| [EDIFACT](#EDIFACT) | Utilise l’encodage EDIFACT. |
| [EXTENDED](#EXTENDED) | Le mode ExtendedCodetext permet de changer manuellement les schémas d’encodage et les encodages ECI dans le codetext. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Utilise l’encodage Text. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Utilise l’encodage ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Encode un caractère alphanumérique ou deux caractères numériques par octet.

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


En mode Auto, le CodeText est encodé avec une compacité maximale des données. Les caractères Unicode sont ré‑encodés dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Encode des valeurs 8 bits.

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Encode des valeurs 8 bits.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Utilise l’encodage C40. Encode les caractères alphanumériques majuscules, les minuscules et les caractères spéciaux.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


En mode ECI, le message complet est ré‑encodé dans l’encodage spécifié ECIEncoding avec l’insertion d’un identifiant ECI. Si un caractère est trouvé qui n’est pas pris en charge par l’encodage ECI sélectionné, une exception est levée. Veuillez noter que certains scanners anciens (pré‑2006) peuvent ne pas prendre en charge ce mode.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Utilise l’encodage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreuses ponctuations, mais ne prend pas en charge les lettres minuscules.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


Le mode ExtendedCodetext permet de changer manuellement les schémas d’encodage et les encodages ECI dans le codetext. Il est préférable d’utiliser DataMatrixExtCodetextBuilder pour la génération de codetext étendu. Utilisez la propriété Display2DText pour définir le texte visible en supprimant les caractères de gestion. Les identifiants ECI sont définis comme une barre oblique unique et un identifiant à six chiffres "\\000026" - identifiant ECI UTF‑8. Tous les caractères Unicode après l’identifiant ECI sont automatiquement encodés dans le jeu de caractères correct. Les schémas d’encodage sont définis au format suivant : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Les schémas d’encodage autorisés sont : EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Tous les antislashs (\\) doivent être doublés dans le texte.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


Le mode ExtendedCodetext permet de changer manuellement les schémas d’encodage et les encodages ECI dans le codetext.

Il est préférable d’utiliser DataMatrixExtCodetextBuilder pour la génération de codetext étendu.

Utilisez la propriété Display2DText pour définir le texte visible en supprimant les caractères de gestion.

Les identifiants ECI sont définis comme une barre oblique unique et un identifiant à six chiffres "\\000026" - identifiant ECI UTF‑8.

Tous les caractères Unicode après l’identifiant ECI sont automatiquement encodés dans le jeu de caractères correct.

Les schémas d’encodage sont définis au format suivant : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Les schémas d’encodage autorisés sont : EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Tous les antislashs (\\) doivent être doublés dans le texte.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Utilise l’encodage Text. Encode les caractères alphanumériques minuscules, majuscules et les caractères spéciaux.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

