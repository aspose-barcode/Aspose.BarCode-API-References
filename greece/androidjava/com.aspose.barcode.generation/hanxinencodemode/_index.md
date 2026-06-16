---
title: HanXinEncodeMode
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Λειτουργία κωδικοποίησης Han Xin Code.
type: docs
weight: 89
url: /el/androidjava/com.aspose.barcode.generation/hanxinencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinEncodeMode extends Enum<HanXinEncodeMode>
```

Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση Auto με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode.

--------------------

> ```
> // Auto mode
>   String codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.save("test.bmp");
> 
> 
>  // Binary mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN)
>  generator.setCodeText(encodedArr);
>  generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>   // ECI mode
>   String codetext = "\u0391\u0392\u0393\u0394\u0395";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
>   generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
>   generator.save("test.bmp");
> 
>   // URI mode
>   String codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.URI);
>   generator.save("test.bmp");
> 
> 
>   // Extended mode
>   String str = "\\gb180302b:\u6f04\\gb180304b:\u3401\\region1:\u5168\\region2:\u8785\\numeric:123\\text:qwe\\\\unicode:\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l" +
>       "\\000009:\u0391\u0392\u0393\u0394\u0395\\auto:abc\\binary:abc\\\\uri:backslashes_should_be_doubled\\\\000555:test";
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> 
>   // Using HanXinExtCodetextBuilder for Extended mode (same codetext as in previous example)
>   //create codetext
>   HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>   codeTextBuilder.addGB18030TwoByte("\u6f04");
>   codeTextBuilder.addGB18030FourByte("\u3401");
>   codeTextBuilder.addCommonChineseRegionOne("\u5168");
>   codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>   codeTextBuilder.addNumeric("123");
>   codeTextBuilder.addText("qwe");
>   codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>   codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>   codeTextBuilder.addAuto("abc");
>   codeTextBuilder.addBinary("abc");
>   codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   //generate codetext
>   String str = codeTextBuilder.getExtendedCodetext();
> 
>   //generate
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> ```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [AUTO](#AUTO) | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [BINARY](#BINARY) | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. |
| [ECI](#ECI) | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. |
| [EXTENDED](#EXTENDED) | Η εκτεταμένη λειτουργία επιτρέπει συνδυασμούς εσωτερικών λειτουργιών: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. |
| [UNICODE](#UNICODE) | Η λειτουργία Unicode σχεδιάζει έναν τρόπο για την αναπαράσταση οποιουδήποτε κειμενικού δεδομένου που αναφέρεται στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στο Han Xin Code. |
| [URI](#URI) | Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι αναφορά Uniform Resource Identifier (URI) στο RFC 3986. |
## Methods

| Method | Περιγραφή |
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
public static final HanXinEncodeMode AUTO
```


Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται χρησιμοποιώντας την κωδικοποίηση GB18030 σύμφωνα με την προδιαγραφή του κώδικα HanXin.

### BINARY {#BINARY}
```
public static final HanXinEncodeMode BINARY
```


In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown.

### ECI {#ECI}
```
public static final HanXinEncodeMode ECI
```


In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode.

### EXTENDED {#EXTENDED}
```
public static final HanXinEncodeMode EXTENDED
```


Η εκτεταμένη λειτουργία επιτρέπει συνδυασμούς εσωτερικών λειτουργιών: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Το Codetext μπορεί να δημιουργηθεί χειροκίνητα με προθέματα και διπλές ανάστροφες κάθετες, π.χ.: @"\\auto:abc\\000009:\\u0391\\u0392\\u0393\\u0394\\u0395\\auto:ab\\\\c" ή χρησιμοποιώντας το HanXinExtCodetextBuilder. Εάν το codetext περιέχει ένα τμήμα ECI, τότε μόνο οι παρακάτω λειτουργίες μπορούν να εμφανιστούν σε αυτό το codetext μετά το τμήμα ECI: Auto, Binary, Text, Numeric, URI, ECI.

### UNICODE {#UNICODE}
```
public static final HanXinEncodeMode UNICODE
```


Η λειτουργία Unicode σχεδιάζει έναν τρόπο για την αναπαράσταση οποιουδήποτε κειμενικού δεδομένου που αναφέρεται στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στο Han Xin Code.

### URI {#URI}
```
public static final HanXinEncodeMode URI
```


Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στο Han Xin Code είναι αναφορά Uniform Resource Identifier (URI) στο RFC 3986.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
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
public static HanXinEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### values() {#values--}
```
public static HanXinEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

