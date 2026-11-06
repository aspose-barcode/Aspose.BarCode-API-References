---
title: "ComplexCodetextReader"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "ComplexCodetextReader, kod metnini belirtilen karmaşık barkod tipine çözer."
type: docs
weight: 13
url: /tr/androidjava/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader, kod metnini belirtilen karmaşık barkod tipine çözer.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | HIBC LIC kod metnini çözer. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | HIBC PAS kod metnini çözer. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Mailmark Barkod C ve L kod metnini çözer. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Royal Mail Mailmark 2D kod metnini çözer. |
| [tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-) | MaxiCode kod metnini çözer. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | SwissQR kod metnini çözer. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | USADriveId kod metnini çözer. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


HIBC LIC kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


HIBC PAS kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Mailmark Barkod C ve L kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Royal Mail Mailmark 2D kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-com.aspose.barcode.generation.MaxiCodeMode-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(MaxiCodeMode maxiCodeMode, String encodedCodetext)
```


MaxiCode kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxiCodeMode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | MaxiCode modu |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


SwissQR kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | kodlanmış kod metni |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


USADriveId kod metnini çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Kodlanmış kod metni |

**Returns:**
[USADriveIdCodetext](../../com.aspose.barcode.complexbarcode/usadriveidcodetext) - Decoded USADriveId or null.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

