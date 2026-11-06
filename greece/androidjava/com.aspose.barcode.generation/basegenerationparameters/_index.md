---
title: "BaseGenerationParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι δημιουργίας εικόνας barcode."
type: docs
weight: 17
url: /el/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

Παράμετροι δημιουργίας εικόνας barcode.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. |
| [getBackColor()](#getBackColor--) | Χρώμα φόντου της εικόνας barcode. |
| [getBarcode()](#getBarcode--) | Λαμβάνει το  BarcodeParameters  που περιέχει όλες τις ιδιότητες του barcode. |
| [getBorder()](#getBorder--) | Λαμβάνει το  BorderParameters  που περιέχει όλες τις ιδιότητες διαμόρφωσης για το περίγραμμα του barcode. |
| [getCaptionAbove()](#getCaptionAbove--) | Λεζάντα Πάνω από την εικόνα BarCode. |
| [getCaptionBelow()](#getCaptionBelow--) | Λεζάντα Κάτω από την εικόνα BarCode. |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | Παράμετροι εικόνας. |
| [getImageHeight()](#getImageHeight--) | Ύψος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getImageWidth--) | Πλάτος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getResolution--) | Λαμβάνει την ανάλυση της εικόνας BarCode. |
| [getRotationAngle()](#getRotationAngle--) | Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. |
| [getUseAntiAlias()](#getUseAntiAlias--) | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. |
| [setBackColor(int value)](#setBackColor-int-) | Χρώμα φόντου της εικόνας barcode. |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | Ύψος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | Πλάτος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. |
| [setResolution(float value)](#setResolution-float-) | Ορίζει την ανάλυση της εικόνας BarCode. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. Προεπιλεγμένη τιμή: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


Χρώμα φόντου της εικόνας barcode. Προεπιλεγμένη τιμή: Color.White. Δείτε  Color .

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


Λαμβάνει το  BarcodeParameters  που περιέχει όλες τις ιδιότητες του barcode.

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


Λαμβάνει το  BorderParameters  που περιέχει όλες τις ιδιότητες διαμόρφωσης για το περίγραμμα του barcode.

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


Λεζάντα Πάνω από την εικόνα BarCode. Δείτε  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


Λεζάντα Κάτω από την εικόνα BarCode. Δείτε  CaptionParameters .

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


Παράμετροι εικόνας. Δείτε .

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


Ύψος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


Πλάτος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


Λαμβάνει την ανάλυση της εικόνας BarCode. Μία τιμή και για τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi.

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας

**Returns:**
boolean
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης. Προεπιλεγμένη τιμή: AutoSizeMode.NONE.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


Χρώμα φόντου της εικόνας barcode. Προεπιλεγμένη τιμή: Color.White. Δείτε  Color .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


Ύψος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


Πλάτος εικόνας BarCode όταν η ιδιότητα  AutoSizeMode  ορίζεται σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Ορίζει την ανάλυση της εικόνας BarCode. Μία τιμή και για τις δύο διαστάσεις. Προεπιλεγμένη τιμή: 96 dpi.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


Γωνία περιστροφής εικόνας BarCode, μετρημένη σε μοίρες, π.χ. RotationAngle = 0 ή RotationAngle = 360 σημαίνει χωρίς περιστροφή. Εάν το RotationAngle ΔΕΝ είναι ίσο με 90, 180, 270 ή 0, μπορεί να αυξήσει τη δυσκολία για το σαρωτή να διαβάσει την εικόνα. Προεπιλεγμένη τιμή: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η λειτουργία anti-aliasing για την απόδοση της εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

