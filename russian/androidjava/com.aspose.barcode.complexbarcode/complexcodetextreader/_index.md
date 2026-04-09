---
title: ComplexCodetextReader
second_title: Справочник API Aspose.BarCode для Android через Java
description: ComplexCodetextReader декодирует кодтекст в указанный тип сложного штрихкода.
type: docs
weight: 13
url: /ru/androidjava/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader декодирует кодтекст в указанный тип сложного штрихкода.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | Декодирует кодовый текст HIBC LIC. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | Декодирует кодовый текст HIBC PAS. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Декодирует кодовый текст штрихкода Mailmark C и L. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Декодирует кодовый текст Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-int-java.lang.String-) | Декодирует кодовый текст MaxiCode. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | Декодирует кодовый текст SwissQR. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | Декодирует кодовый текст USADriveId. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Декодирует кодовый текст HIBC LIC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


Декодирует кодовый текст HIBC PAS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Декодирует кодовый текст штрихкода Mailmark C и L.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Декодирует кодовый текст Royal Mail Mailmark 2D.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-int-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)
```


Декодирует кодовый текст MaxiCode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxiCodeMode | int | режим MaxiCode |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


Декодирует кодовый текст SwissQR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | закодированный кодовый текст |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


Декодирует кодовый текст USADriveId.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Encoded codetext |

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext - Decoded USADriveId or null.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

