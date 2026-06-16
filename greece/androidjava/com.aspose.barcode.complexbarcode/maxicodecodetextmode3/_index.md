---
title: MaxiCodeCodetextMode3
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 3.
type: docs
weight: 27
url: /el/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode3 extends MaxiCodeStructuredCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode για λειτουργίες 3. Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το MaxiCode codetext για τη λειτουργία 3.

```
//Mode 3 with standart second message
  MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
  maxiCodeCodetext.setPostalCode("B1050");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStandartSecondMessage maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
  maxiCodeStandartSecondMessage.setMessage("Test message");
  maxiCodeCodetext.setSecondMessage(maxiCodeStandartSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Mode 3 with structured second message
  MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
  maxiCodeCodetext.setPostalCode("B1050");
  maxiCodeCodetext.setCountryCode(056);
  maxiCodeCodetext.setServiceCategory(999);
  MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
  maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
  maxiCodeStructuredSecondMessage.add("PITTSBURGH");
  maxiCodeStructuredSecondMessage.add("PA");
  maxiCodeStructuredSecondMessage.setYear(99);
  maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
  ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
  complexGenerator.generateBarCodeImage();

  //Decoding raw codetext with standart second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for(BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
      {
          MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
          if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStandartSecondMessage)
          {
              MaxiCodeStandartSecondMessage secondMessage = (MaxiCodeStandartSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
              System.out.println("Message: " + secondMessage.getMessage());
          }
      }
  }
  //Decoding raw codetext with structured second message
  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for(BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceOf MaxiCodeCodetextMode3)
      {
          MaxiCodeCodetextMode3 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode3)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
          if (maxiCodeStructuredCodetext.getSecondMessage() instanceOf MaxiCodeStructuredSecondMessage)
          {
              MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.getSecondMessage();
              System.out.println("Message:");
              for(String identifier : secondMessage.getIdentifiers())
              {
                  System.out.println(identifier);
              }
          }
      }
  }
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [MaxiCodeCodetextMode3()](#MaxiCodeCodetextMode3--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified MaxiCodeStructuredCodetext value. |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί το codetext. |
| [getCountryCode()](#getCountryCode--) | Identifies 3 digit country code. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMode()](#getMode--) | Gets MaxiCode mode. |
| [getPostalCode()](#getPostalCode--) | Identifies the postal code. |
| [getSecondMessage()](#getSecondMessage--) | Identifies second message of the barcode. |
| [getServiceCategory()](#getServiceCategory--) | Identifies 3 digit service category. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί την παρουσία από το δημιουργημένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifies 3 digit country code. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει κωδικοποίηση ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Identifies the postal code. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifies second message of the barcode. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifies 3 digit service category. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetextMode3() {#MaxiCodeCodetextMode3--}
```
public MaxiCodeCodetextMode3()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified MaxiCodeStructuredCodetext value.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή MaxiCodeStructuredCodetext για σύγκριση με αυτήν την παρουσία |

**Returns:**
boolean - **true** εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά, **false**
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
public String getConstructedCodetext()
```


Δημιουργεί το codetext.

**Returns:**
java.lang.String - Constructed codetext
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Identifies 3 digit country code.

**Returns:**
int
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
public int getMode()
```


Gets MaxiCode mode.

**Returns:**
int - λειτουργία MaxiCode
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Identifies second message of the barcode.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Identifies 3 digit service category.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
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




### setCountryCode(int value) {#setCountryCode-int-}
```
public void setCountryCode(int value)
```


Identifies 3 digit country code.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Αναγνωρίζει τον ταχυδρομικό κώδικα. Πρέπει να είναι 9 ψηφία στη λειτουργία 2 ή 6 αλφαριθμητικά σύμβολα στη λειτουργία 3.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifies second message of the barcode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Identifies 3 digit service category.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

