---
title: ComplexCodetextReader
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: ComplexCodetextReader décode le texte du code vers le type de code‑barres complexe spécifié.
type: docs
weight: 13
url: /fr/androidjava/com.aspose.barcode.complexbarcode/complexcodetextreader/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexCodetextReader
```

ComplexCodetextReader décode le texte du code vers le type de code‑barres complexe spécifié.

--------------------

> ```
> This sample shows how to recognize and decode SwissQR image.
>   
>   BarCodeReader cr = new BarCodeReader("SwissQRCodetext.png", DecodeType.QR);
>   cr.read();
>   SwissQRCodetext result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText());
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryDecodeHIBCLIC(String encodedCodetext)](#tryDecodeHIBCLIC-java.lang.String-) | Décode le texte de code HIBC LIC. |
| [tryDecodeHIBCPAS(String encodedCodetext)](#tryDecodeHIBCPAS-java.lang.String-) | Décode le texte de code HIBC PAS. |
| [tryDecodeMailmark(String encodedCodetext)](#tryDecodeMailmark-java.lang.String-) | Décode le texte de code Mailmark Barcode C et L. |
| [tryDecodeMailmark2D(String encodedCodetext)](#tryDecodeMailmark2D-java.lang.String-) | Décode le texte de code Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)](#tryDecodeMaxiCode-int-java.lang.String-) | Décode le texte de code MaxiCode. |
| [tryDecodeSwissQR(String encodedCodetext)](#tryDecodeSwissQR-java.lang.String-) | Décode le texte de code SwissQR. |
| [tryDecodeUSADriveId(String encodedCodetext)](#tryDecodeUSADriveId-java.lang.String-) | Décode le texte de code USADriveId. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Décode le texte de code HIBC LIC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext) - decoded HIBC LIC Complex Codetext or null.
### tryDecodeHIBCPAS(String encodedCodetext) {#tryDecodeHIBCPAS-java.lang.String-}
```
public static HIBCPASCodetext tryDecodeHIBCPAS(String encodedCodetext)
```


Décode le texte de code HIBC PAS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[HIBCPASCodetext](../../com.aspose.barcode.complexbarcode/hibcpascodetext) - decoded HIBC PAS Complex Codetext or null.
### tryDecodeMailmark(String encodedCodetext) {#tryDecodeMailmark-java.lang.String-}
```
public static MailmarkCodetext tryDecodeMailmark(String encodedCodetext)
```


Décode le texte de code Mailmark Barcode C et L.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[MailmarkCodetext](../../com.aspose.barcode.complexbarcode/mailmarkcodetext) - Decoded Mailmark Barcode C and L or null.
### tryDecodeMailmark2D(String encodedCodetext) {#tryDecodeMailmark2D-java.lang.String-}
```
public static Mailmark2DCodetext tryDecodeMailmark2D(String encodedCodetext)
```


Décode le texte de code Royal Mail Mailmark 2D.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[Mailmark2DCodetext](../../com.aspose.barcode.complexbarcode/mailmark2dcodetext) - decoded Royal Mail Mailmark 2D or null.
### tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext) {#tryDecodeMaxiCode-int-java.lang.String-}
```
public static MaxiCodeCodetext tryDecodeMaxiCode(int maxiCodeMode, String encodedCodetext)
```


Décode le texte de code MaxiCode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxiCodeMode | int | Mode MaxiCode |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext) - Decoded MaxiCode codetext.
### tryDecodeSwissQR(String encodedCodetext) {#tryDecodeSwissQR-java.lang.String-}
```
public static SwissQRCodetext tryDecodeSwissQR(String encodedCodetext)
```


Décode le texte de code SwissQR.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | texte de code encodé |

**Returns:**
[SwissQRCodetext](../../com.aspose.barcode.complexbarcode/swissqrcodetext) - decoded SwissQRCodetext or null.
### tryDecodeUSADriveId(String encodedCodetext) {#tryDecodeUSADriveId-java.lang.String-}
```
public static USADriveIdCodetext tryDecodeUSADriveId(String encodedCodetext)
```


Décode le texte de code USADriveId.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encodedCodetext | java.lang.String | Texte de code encodé |

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext - USADriveId décodé ou null.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

