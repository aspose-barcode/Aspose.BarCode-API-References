---
title: QualitySettings
second_title: Aspose.BarCode for Android via Java API-referens
description: QualitySettings tillåter att konfigurera igenkänningskvalitet och hastighet manuellt.
type: docs
weight: 44
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings tillåter att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in QualitySettings med inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxQuality eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality.

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

| Constructor | Beskrivning |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings konstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Läge som möjliggör eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [getDeconvolution()](#getDeconvolution--) | Dekonvolution (bildåterställning) läge som definierar nivån på bildnedbrytning. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance-igenkänningskvalitetsförinställning. |
| [getHighQuality()](#getHighQuality--) | HighQuality-igenkänningskvalitetsförinställning. |
| [getImageScalingMode()](#getImageScalingMode--) | Tillåter att skala bilden med den specifika ImageScaleMode. |
| [getInverseImage()](#getInverseImage--) | Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality-igenkänningskvalitetsförinställning. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality-igenkänningskvalitetsförinställning. |
| [getXDimension()](#getXDimension--) | Igenkänningsläge som anger storlek (från 1 till oändlig) för streckkodens minsta element: matriscell eller stapel. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Läge som möjliggör eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Dekonvolution (bildåterställning) läge som definierar nivån på bildnedbrytning. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Tillåter att skala bilden med den specifika ImageScaleMode-värdet: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Igenkänningsläge som anger storlek (från 1 till oändlig) för streckkodens minsta element: matriscell eller stapel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings konstruktor

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text.

Värde: Tillåter motorn att känna igen felaktiga streckkoder.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver hårdare metoder vilket saktar ner igenkänningen.

Värde: Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten.

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


Läge som möjliggör eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder.

Värde: Ytterligare igenkänning av färgstreckkoder på färgbilder.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Dekonvolution (bildåterställning) läge som definierar nivån på bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka bildfunktionen som korrumperar bilden, måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi.

Värde: Dekonvolution-läge som definierar nivån på bildnedbrytning.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance-igenkänningskvalitetsförinställning. Streckkoder av hög kvalitet känns igen väl i detta läge.

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

Värde: HighPerformance-igenkänningskvalitetsförinställning.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality-recognationskvalitetspreset. Detta preset är utvecklat för streckkoder med låg kvalitet. Tillåter att upptäcka kraftigt skadade streckkoder.

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

Värde: HighQuality recognationskvalitetspreset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Tillåter att skala bilden med den specifika ImageScaleMode.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

Värde: Ytterligare igenkänning av streckkoder på bilder med omvända färger

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality-recognationskvalitetspreset. Detta preset är utvecklat för att känna igen alla möjliga streckkoder, även felaktiga streckkoder.

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

Värde: MaxQuality recognationskvalitetspreset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension.

Värde: Minimal storlek på XDimension i pixlar som används med UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality-recognationskvalitetspreset. Lämplig för de flesta streckkoder

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

Värde: NormalQuality recognationskvalitetspreset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Igenkänningsläge som anger storlek (från 1 till oändlig) för streckkodens minsta element: matriscell eller stapel.

Värde: storlek (från 1 till oändlig) av streckkodens minsta element: matriscell eller stapel.

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


Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text.

Värde: Tillåter motorn att känna igen felaktiga streckkoder.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver hårdare metoder vilket saktar ner igenkänningen.

Värde: Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Läge som möjliggör eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder.

Värde: Ytterligare igenkänning av färgstreckkoder på färgbilder.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Dekonvolution (bildåterställning) läge som definierar nivån på bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka bildfunktionen som korrumperar bilden, måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi.

Värde: Dekonvolution-läge som definierar nivån på bildnedbrytning.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Tillåter att skala bilden med den specifika ImageScaleMode-värdet:

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode värde |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Läge som möjliggör eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

Värde: Ytterligare igenkänning av streckkoder på bilder med omvända färger

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension.

Värde: Minimal storlek på XDimension i pixlar som används med UseMinimalXDimension.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Igenkänningsläge som anger storlek (från 1 till oändlig) för streckkodens minsta element: matriscell eller stapel.

Värde: storlek (från 1 till oändlig) av streckkodens minsta element: matriscell eller stapel.

**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

