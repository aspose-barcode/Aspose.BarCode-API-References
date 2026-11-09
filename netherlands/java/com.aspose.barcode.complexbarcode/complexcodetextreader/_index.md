---
title: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Java API-referentie"
description: "ComplexCodetextReader decodeert codetext naar het opgegeven type complexe barcode."
type: docs
weight: 13
url: /nl/java/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader decodeert codetext naar het opgegeven type complexe barcode.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | Decodeert HIBC LIC-codetekst. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | Decodeert HIBC PAS-codetekst. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Decodeert Mailmark Barcode C en L codetekst. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Decodeert Royal Mail Mailmark 2D-codetekst. |
| [tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-) | Decodeert MaxiCode-codetekst. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | Decodeert SwissQR-codetekst. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | Decodeert USADriveId-codetekst. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Decodeert HIBC LIC-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


Decodeert HIBC PAS-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Decodeert Mailmark Barcode C en L codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Decodeert Royal Mail Mailmark 2D-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)
```


Decodeert MaxiCode-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxiCodeMode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | MaxiCode-modus |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


Decodeert SwissQR-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | gecodeerde codetekst |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


Decodeert USADriveId-codetekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Gecodeerde codetekst |

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

