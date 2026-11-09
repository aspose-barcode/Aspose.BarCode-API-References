---
title: "ComplexCodetextReader"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "ComplexCodetextReader decodifica il testo del codice nel tipo di barcode complesso specificato."
type: docs
weight: 13
url: /it/java/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader decodifica il testo del codice nel tipo di barcode complesso specificato.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | Decodifica il codetext HIBC LIC. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | Decodifica il codetext HIBC PAS. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Decodifica il codetext Mailmark Barcode C e L. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Decodifica il codetext Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-) | Decodifica il codetext MaxiCode. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | Decodifica il codetext SwissQR. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | Decodifica il codetext USADriveId. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Decodifica il codetext HIBC LIC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


Decodifica il codetext HIBC PAS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Decodifica il codetext Mailmark Barcode C e L.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Decodifica il codetext Royal Mail Mailmark 2D.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)
```


Decodifica il codetext MaxiCode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxiCodeMode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | Modalità MaxiCode |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


Decodifica il codetext SwissQR.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | codetext codificato |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


Decodifica il codetext USADriveId.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Codetext codificato |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

