---
title: MaxiCodeCodetext
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode.
type: docs
weight: 25
url: /el/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode.

Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε ακατέργαστο κείμενο MaxiCode σε παρουσία MaxiCodeCodetext.

```

 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί το codetext. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί την παρουσία από το δημιουργημένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει κωδικοποίηση ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Λαμβάνει τον τύπο barcode.

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
public abstract String getConstructedCodetext()
```


Δημιουργεί το codetext.

**Returns:**
java.lang.String - Constructed codetext
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Λαμβάνει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Returns:**
int - κωδικοποίηση ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - λειτουργία MaxiCode
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
```


Αρχικοποιεί την παρουσία από το δημιουργημένο codetext.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ορίζει κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Κωδικοποίηση ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | μια λειτουργία κωδικοποίησης MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | μια λειτουργία κωδικοποίησης MaxiCode. |

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

