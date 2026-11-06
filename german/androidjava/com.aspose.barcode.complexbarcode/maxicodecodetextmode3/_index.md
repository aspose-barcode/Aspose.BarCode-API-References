---
title: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Klasse zum Codieren und Dekodieren des im MaxiCode‑Code für Modus 3 eingebetteten Textes."
type: docs
weight: 27
url: /de/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode3 extends MaxiCodeStructuredCodetext
```

Klasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes für Modus 3. Dieses Beispiel zeigt, wie man MaxiCode-Codetext für Modus 3 kodiert und dekodiert.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MaxiCodeCodetextMode3()](#MaxiCodeCodetextMode3--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)-Wert entspricht. |
| [getBarcodeType()](#getBarcodeType--) | Liest den Barcode-Typ. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Erstellt Codetext |
| [getCountryCode()](#getCountryCode--) | Identifiziert den dreistelligen Ländercode. |
| [getECIEncoding()](#getECIEncoding--) | Liest die ECI-Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Ermittelt einen MaxiCode-Kodierungsmodus. |
| [getMode()](#getMode--) | Liest den MaxiCode-Modus. |
| [getPostalCode()](#getPostalCode--) | Identifiziert die Postleitzahl. |
| [getSecondMessage()](#getSecondMessage--) | Identifiziert die zweite Nachricht des Barcodes. |
| [getServiceCategory()](#getServiceCategory--) | Identifiziert die dreistellige Servicekategorie. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialisiert die Instanz aus dem konstruierten Codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifiziert den dreistelligen Ländercode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Kodierung. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Kodiermodus. |
| [setPostalCode(String postalCode)](#setPostalCode-java.lang.String-) |  |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifiziert die zweite Nachricht des Barcodes. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifiziert die dreistellige Servicekategorie. |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)-Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**, wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Liest den Barcode-Typ.

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


Erstellt Codetext

**Returns:**
java.lang.String - Konstruktierter Codetext
### getCountryCode() {#getCountryCode--}
```
public final int getCountryCode()
```


Identifiziert den dreistelligen Ländercode.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Liest die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Kodierung.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Liest einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


Liest den MaxiCode-Modus.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Identifiziert die Postleitzahl. Muss im Modus 2 aus 9 Ziffern oder im Modus 3 aus 6 alphanumerischen Zeichen bestehen.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public final MaxiCodeSecondMessage getSecondMessage()
```


Identifiziert die zweite Nachricht des Barcodes.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public final int getServiceCategory()
```


Identifiziert die dreistellige Servicekategorie.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer‑Hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialisiert die Instanz aus dem konstruierten Codetext.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Konstruktierter Codetext. |

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


Identifiziert den dreistelligen Ländercode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Kodierung. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Kodiermodus. |

### setPostalCode(String postalCode) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String postalCode)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| postalCode | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public final void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifiziert die zweite Nachricht des Barcodes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public final void setServiceCategory(int value)
```


Identifiziert die dreistellige Servicekategorie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

