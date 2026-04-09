---
title: MaxiCodeCodetextMode3
second_title: Aspose.BarCode for Android via Java API-referentie
description: Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 3.
type: docs
weight: 27
url: /nl/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetextmode3/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext), [com.aspose.barcode.complexbarcode.MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext)
```
public class MaxiCodeCodetextMode3 extends MaxiCodeStructuredCodetext
```

Klasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code voor modus 3. Deze voorbeeld toont hoe MaxiCode-codetekst te coderen en decoderen voor modus 3.

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

| Constructor | Beschrijving |
| --- | --- |
| [MaxiCodeCodetextMode3()](#MaxiCodeCodetextMode3--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven MaxiCodeStructuredCodetext-waarde. |
| [getBarcodeType()](#getBarcodeType--) | Haalt barcode‑type op. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construeert codetext |
| [getCountryCode()](#getCountryCode--) | Identificeert de 3-cijferige landcode. |
| [getECIEncoding()](#getECIEncoding--) | Haalt ECI-codering op. |
| [getEncodeMode()](#getEncodeMode--) | Haalt een MaxiCode-coderingmodus op. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Haalt een MaxiCode-coderingmodus op. |
| [getMode()](#getMode--) | Haalt MaxiCode-modus op. |
| [getPostalCode()](#getPostalCode--) | Identificeert de postcode. |
| [getSecondMessage()](#getSecondMessage--) | Identificeert het tweede bericht van de barcode. |
| [getServiceCategory()](#getServiceCategory--) | Identificeert de 3-cijferige servicecategorie. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identificeert de 3-cijferige landcode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Stelt ECI-codering in. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Stelt een MaxiCode-coderingsmodus in. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Stelt een MaxiCode-coderingsmodus in. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Identificeert de postcode. |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identificeert het tweede bericht van de barcode. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identificeert de 3-cijferige servicecategorie. |
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


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven MaxiCodeStructuredCodetext-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een MaxiCodeStructuredCodetext-waarde om te vergelijken met deze instantie |

**Returns:**
boolean - **true** als obj dezelfde waarde heeft als deze instantie; anders, **false**
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Haalt barcode‑type op.

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


Construeert codetext

**Returns:**
java.lang.String - Gemaakt codetext
### getCountryCode() {#getCountryCode--}
```
public int getCountryCode()
```


Identificeert de 3-cijferige landcode.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int - ECI-codering.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Haalt een MaxiCode-coderingsmodus op. Standaardwaarde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Haalt een MaxiCode-coderingsmodus op. Standaardwaarde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public int getMode()
```


Haalt MaxiCode-modus op.

**Returns:**
int - MaxiCode-modus
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public MaxiCodeSecondMessage getSecondMessage()
```


Identificeert het tweede bericht van de barcode.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public int getServiceCategory()
```


Identificeert de 3-cijferige servicecategorie.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initialiseert instantie vanuit geconstrueerde codetext.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Gemaakt codetext. |

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


Identificeert de 3-cijferige landcode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | ECI-codering. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Stelt een MaxiCode-coderingsmodus in. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | een MaxiCode-coderingsmodus. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Stelt een MaxiCode-coderingsmodus in. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | een MaxiCode-coderingsmodus. |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public void setSecondMessage(MaxiCodeSecondMessage value)
```


Identificeert het tweede bericht van de barcode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public void setServiceCategory(int value)
```


Identificeert de 3-cijferige servicecategorie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

