---
title: "ComplexCodetextReader"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट जटिल बारकोड प्रकार में डिकोड करता है।"
type: docs
weight: 13
url: /hi/java/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट जटिल बारकोड प्रकार में डिकोड करता है।

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | HIBC LIC codetext को डिकोड करता है। |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | HIBC PAS codetext को डिकोड करता है। |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Mailmark Barcode C और L codetext को डिकोड करता है। |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Royal Mail Mailmark 2D codetext को डिकोड करता है। |
| [tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-) | MaxiCode codetext को डिकोड करता है। |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | SwissQR codetext को डिकोड करता है। |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | USADriveId codetext को डिकोड करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryDecodeHIBCLIC(String encodedCodetext) {#tryDecodeHIBCLIC-java.lang.String-}
```
public static HIBCLICComplexCodetext tryDecodeHIBCLIC(String encodedCodetext)
```


HIBC LIC codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


HIBC PAS codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Mailmark Barcode C और L codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Royal Mail Mailmark 2D codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)
```


MaxiCode codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxiCodeMode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | MaxiCode मोड |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


SwissQR codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


USADriveId codetext को डिकोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodedCodetext | java.lang.String | एन्कोडेड codetext |

**Returns:**
[USADriveIdCodetext](../../com.aspose.barcode.complexbarcode/usadriveidcodetext) - Decoded USADriveId or null.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

