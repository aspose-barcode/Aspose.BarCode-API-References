---
title: "QualitySettings"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit."
type: docs
weight: 40
url: /de/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality, oder Sie können die einzelnen Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet. |
| [getDeconvolution()](#getDeconvolution--) | Deconvolution‑Modus (Bildrestaurierung), der das Ausmaß der Bilddegradation definiert. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance‑Erkennungsqualitäts‑Voreinstellung. |
| [getHighQuality()](#getHighQuality--) | HighQuality‑Erkennungsqualitäts‑Voreinstellung. |
| [getInverseImage()](#getInverseImage--) | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet. |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality‑Erkennungsqualitäts‑Voreinstellung. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality‑Erkennungsqualitäts‑Voreinstellung. |
| [getXDimension()](#getXDimension--) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Deconvolution‑Modus (Bildrestaurierung), der das Ausmaß der Bilddegradation definiert. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

Wert: Ermöglicht der Engine, fehlerhafte Barcodes zu erkennen.

**Returns:**
boolesch
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

Wert: Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen.

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet.

Wert: Zusätzliche Erkennung von Farbcodes in Farbbildern.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Deconvolution (Bildrestaurierung) Modus, der das Ausmaß der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch irgendeine natürliche Funktion wie Unschärfe (Blur) degradiertes (konvolutiertes) Bild wiederherstellen kann, das beim Aufnehmen mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

Wert: Deconvolution-Modus, der das Niveau der Bildverschlechterung definiert.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance-Erkennungsqualitäts-Voreinstellung. Hochwertige Barcodes werden in diesem Modus gut erkannt.

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Wert: HighPerformance-Erkennungsqualitäts-Voreinstellung.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality-Erkennungsqualitäts-Voreinstellung. Diese Voreinstellung wurde für Barcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Barcodes.

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Wert: HighQuality-Erkennungsqualitäts-Voreinstellung.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet.

Wert: Zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality-Erkennungsqualitäts-Voreinstellung. Diese Voreinstellung wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes.

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Wert: MaxQuality-Erkennungsqualitäts-Voreinstellung.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

Wert: Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality-Erkennungsqualitäts-Voreinstellung. Geeignet für die meisten Barcodes

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

Wert: NormalQuality-Erkennungsqualitäts-Voreinstellung.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich.

Wert: Größe (von 1 bis unendlich) des minimalen Barcode-Elements: Matrixzelle oder Strich.

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
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




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

Wert: Ermöglicht der Engine, fehlerhafte Barcodes zu erkennen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

Wert: Modus, der Methoden ermöglicht, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern ein- oder ausschaltet.

Wert: Zusätzliche Erkennung von Farbcodes in Farbbildern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Deconvolution (Bildrestaurierung) Modus, der das Ausmaß der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch irgendeine natürliche Funktion wie Unschärfe (Blur) degradiertes (konvolutiertes) Bild wiederherstellen kann, das beim Aufnehmen mit einer Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

Wert: Deconvolution-Modus, der das Niveau der Bildverschlechterung definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) ein- oder ausschaltet.

Wert: Zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

Wert: Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich.

Wert: Größe (von 1 bis unendlich) des minimalen Barcode-Elements: Matrixzelle oder Strich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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
public final native void wait(long arg0)
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

