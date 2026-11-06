---
title: "AustraliaPostSettings"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι αποκωδικοποίησης AustraliaPost."
type: docs
weight: 10
url: /el/androidjava/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

Παράμετροι αποκωδικοποίησης AustraliaPost. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα της συμβολιστικής AustraliaPost.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | Δημόσια διεπαφή για την αποκωδικοποίηση του πεδίου Customer Information Field που χρησιμοποιείται στη συμβολική AustraliaPost. |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | Λαμβάνει ή ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER. |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | Δημόσια διεπαφή για την αποκωδικοποίηση του πεδίου Customer Information Field που χρησιμοποιείται στη συμβολική AustraliaPost. |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | Λαμβάνει ή ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER. |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
### getCustomerInformationDecoder() {#getCustomerInformationDecoder--}
```
public AustraliaPostCustomerInformationDecoder getCustomerInformationDecoder()
```


Δημόσια διεπαφή για την αποκωδικοποίηση του πεδίου Customer Information Field που χρησιμοποιείται στη συμβολική AustraliaPost.

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


Λαμβάνει ή ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER.

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία "333" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα "z". Παράδειγμα BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος κατά τη διάρκεια της αποκωδικοποίησης με τη μέθοδο CTable
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




### setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value) {#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-}
```
public void setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)
```


Δημόσια διεπαφή για την αποκωδικοποίηση του πεδίου Customer Information Field που χρησιμοποιείται στη συμβολική AustraliaPost.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


Λαμβάνει ή ορίζει τον Τύπο Ερμηνείας για τις Πληροφορίες Πελάτη του AustralianPost BarCode. Η προεπιλογή είναι CustomerInformationInterpretingType.OTHER.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Ο τύπος ερμηνείας (CTable, NTable ή Other) των πληροφοριών πελάτη για το AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία "333" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα "z". Παράδειγμα BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

