---
title: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Ορίζει τον τύπο ερμηνείας typeC_TABLE ή N_TABLE των πληροφοριών πελάτη για το AustralianPost BarCode."
type: docs
weight: 51
url: /el/java/com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum CustomerInformationInterpretingType extends Enum<CustomerInformationInterpretingType>
```

Ορίζει τον τύπο ερμηνείας (C\_TABLE ή N\_TABLE) των πληροφοριών πελάτη για το AustralianPost BarCode.

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε το barcode Australia Post με τον τύπο ερμηνείας CTable.

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde");
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
>   BufferedImage image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456781234567"))
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.N_TABLE);
>   BufferedImage image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST))
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.N_TABLE);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```

--------------------

> ```
> BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456780123012301230123");
>   generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.OTHER);
>   BufferedImage image = generator.generateBarCodeImage();
>   BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
>   reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.OTHER);
>   for(BarCodeResult result : reader.readBarCodes())
>   {
>       System.out.println("BarCode Type: " + result.getCodeType());
>       System.out.println("BarCode CodeText: " + result.getCodeText());
>   }
> ```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [C_TABLE](#C-TABLE) | Χρησιμοποιήστε C\_TABLE για να ερμηνεύσετε τις πληροφορίες πελάτη. |
| [N_TABLE](#N-TABLE) | Χρησιμοποιήστε N\_TABLE για να ερμηνεύσετε τις πληροφορίες του πελάτη. |
| [OTHER](#OTHER) | Μην ερμηνεύετε τις πληροφορίες του πελάτη. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
### C_TABLE {#C-TABLE}
```
public static final CustomerInformationInterpretingType C_TABLE
```


Χρησιμοποιήστε C\_TABLE για να ερμηνεύσετε τις πληροφορίες του πελάτη. Επιτρέπει A..Z, a..z, 1..9, κενό και \# σύμβολο.

### N_TABLE {#N-TABLE}
```
public static final CustomerInformationInterpretingType N_TABLE
```


Χρησιμοποιήστε N\_TABLE για να ερμηνεύσετε τις πληροφορίες του πελάτη. Επιτρέπει ψηφία.

### OTHER {#OTHER}
```
public static final CustomerInformationInterpretingType OTHER
```


Μην ερμηνεύετε τις πληροφορίες του πελάτη. Επιτρέπει μόνο το σύμβολο 0, 1, 2 ή 3.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static CustomerInformationInterpretingType fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype)
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
public static CustomerInformationInterpretingType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype)
### values() {#values--}
```
public static CustomerInformationInterpretingType[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

