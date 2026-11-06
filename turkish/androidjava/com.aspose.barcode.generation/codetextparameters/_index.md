---
title: "CodetextParameters"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Kod metni parametreleri."
type: docs
weight: 26
url: /tr/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Kod metni parametreleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Kod metninin hizalamasını alır. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Görüntülenen CodeText'in rengini belirtin. |
| [getFont()](#getFont--) | Görüntülenen CodeText'in yazı tipini belirtin. |
| [getFontMode()](#getFontMode--) | FontMode'u belirtin. |
| [getLocation()](#getLocation--) | Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Metin içinde kelime kaydırmalarını (satır sonlarını) belirtin.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | CodeText ile BarCode arasındaki boşluk, Unit değerinde. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2D barkodlarda codetext yerine görüntülenecek metin. |
| [toString()](#toString--) | Bu CodetextParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Kod metninin hizalamasını alır. Varsayılan değer: TextAlignment.CENTER.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public int getColor()
```


Görüntülenen CodeText'in rengini belirtin. Varsayılan değer: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Görüntülenen CodeText'in yazı tipini belirtin. Varsayılan değer: Arial 5pt regular. FontMode, FontMode.AUTO olarak ayarlanmışsa yok sayılır.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. Özellikle AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION içinde FontMode.AUTO kullanılması önerilir. Varsayılan değer: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın. Varsayılan değer: 1D barkodlar için CodeLocation.BELOW ve 2D barkodlar için CodeLocation.None.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText ile BarCode arasındaki boşluk, Unit değerinde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D barkodlarda codetext yerine görüntülenecek metin. Kullanıldığı yerler: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Kod metninin hizalamasını ayarlar. Varsayılan değer: TextAlignment.CENTER.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Görüntülenen CodeText'in rengini belirtin. Varsayılan değer: Color.BLACK.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Görüntülenen CodeText'in yazı tipini belirtin. Varsayılan değer: Arial 5pt regular. FontMode, FontMode.AUTO olarak ayarlanmışsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. Özellikle AutoSizeMode.NEAREST veya AutoSizeMode.INTERPOLATION içinde FontMode.AUTO kullanılması önerilir. Varsayılan değer: FontMode.AUTO.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın. Varsayılan değer: 1D barkodlar için CodeLocation.BELOW ve 2D barkodlar için CodeLocation.None.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


CodeText ile BarCode arasındaki boşluk, Unit değerinde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D barkodlarda codetext yerine görüntülenecek metin. Kullanıldığı yerler: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Bu CodetextParameters nesnesinin insan tarafından okunabilir dize temsilini döndürür.

**Returns:**
java.lang.String - Bu CodetextParameters nesnesini temsil eden bir dize.
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

