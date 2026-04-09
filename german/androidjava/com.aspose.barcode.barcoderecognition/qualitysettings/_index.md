---
title: QualitySettings
second_title: Aspose.BarCode für Android via Java API-Referenz
description: QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit.
type: docs
weight: 44
url: /de/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality oder Sie können die einzelnen Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings Konstruktor |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche checksumm oder falsche Werte haben. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert. |
| [getDeconvolution()](#getDeconvolution--) | Deconvolution‑Modus (Bildwiederherstellung), der das Ausmaß der Bilddegradation definiert. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance‑Erkennungsqualitätsvorgabe. |
| [getHighQuality()](#getHighQuality--) | HighQuality‑Erkennungsqualitätsvorgabe. |
| [getImageScalingMode()](#getImageScalingMode--) | Ermöglicht das Skalieren des Bildes mit dem spezifischen ImageScaleMode. |
| [getInverseImage()](#getInverseImage--) | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality‑Erkennungsqualitätsvorgabe. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality‑Erkennungsqualitätsvorgabe. |
| [getXDimension()](#getXDimension--) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche checksumm oder falsche Werte haben. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Deconvolution‑Modus (Bildwiederherstellung), der das Ausmaß der Bilddegradation definiert. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Ermöglicht das Skalieren des Bildes mit dem spezifischen ImageScaleMode‑Wert: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings Konstruktor

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche checksumm oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

Wert: Ermöglicht der Engine, fehlerhafte Barcodes zu erkennen.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

Wert: Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen.

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


Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert.

Wert: Zusätzliche Erkennung von Farbcodes in Farbbildern.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Deconvolution‑Modus (Bildwiederherstellung), der das Ausmaß der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine beliebige natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, die beim Aufnehmen des Bildes mit der Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie sharp oder mathematische Morphologie prüfen.

Wert: Deconvolution‑Modus, der das Ausmaß der Bilddegradation definiert.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance‑Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus gut erkannt.

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

Wert: HighPerformance‑Erkennungsqualitätsvorgabe.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe wurde für Barcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Barcodes.

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

Wert: HighQuality-Erkennungsqualitätsvorgabe.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Ermöglicht das Skalieren des Bildes mit dem spezifischen ImageScaleMode.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert.

Wert: Zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes.

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

Wert: MaxQuality-Erkennungsqualitätsvorgabe.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

Wert: Minimale Größe der XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality-Erkennungsqualitätsvorgabe. Geeignet für die meisten Barcodes

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

Wert: NormalQuality-Erkennungsqualitätsvorgabe.

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


Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche checksumm oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

Wert: Ermöglicht der Engine, fehlerhafte Barcodes zu erkennen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode‑Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt.

Wert: Modus, der Methoden aktiviert, Barcode‑Elemente mit der ausgewählten Qualität zu erkennen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert.

Wert: Zusätzliche Erkennung von Farbcodes in Farbbildern.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Deconvolution‑Modus (Bildwiederherstellung), der das Ausmaß der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine beliebige natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, die beim Aufnehmen des Bildes mit der Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie sharp oder mathematische Morphologie prüfen.

Wert: Deconvolution‑Modus, der das Ausmaß der Bilddegradation definiert.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Ermöglicht das Skalieren des Bildes mit dem spezifischen ImageScaleMode‑Wert:

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode-Wert |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Modus, der die zusätzliche Erkennung von Barcodes in Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert.

Wert: Zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

Wert: Minimale Größe der XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode‑Elements festlegt: Matrixzelle oder Strich.

Wert: Größe (von 1 bis unendlich) des minimalen Barcode-Elements: Matrixzelle oder Strich.

**Parameters:**
| Parameter | Type | Beschreibung |
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

