---
title: QualitySettings
second_title: Aspose.BarCode for Android via Java API-referentie
description: QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren.
type: docs
weight: 44
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt snel QualitySettings instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality of je kunt handmatig afzonderlijke opties configureren. Standaardwaarde van QualitySettings is NormalQuality.

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

| Constructor | Beschrijving |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings constructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Staat de engine toe om barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Modus die extra herkenning van kleur‑barcodes op kleurafbeeldingen in- of uitschakelt. |
| [getDeconvolution()](#getDeconvolution--) | Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance herkenningskwaliteits‑preset. |
| [getHighQuality()](#getHighQuality--) | HighQuality herkenningskwaliteits‑preset. |
| [getImageScalingMode()](#getImageScalingMode--) | Staat toe de afbeelding te schalen met de specifieke ImageScaleMode |
| [getInverseImage()](#getInverseImage--) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality herkenningskwaliteits‑preset. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality herkenningskwaliteits‑preset. |
| [getXDimension()](#getXDimension--) | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Staat de engine toe om barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Modus die extra herkenning van kleur‑barcodes op kleurafbeeldingen in- of uitschakelt. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Staat toe de afbeelding te schalen met de specifieke ImageScaleMode Waarde: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings constructor

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Staat de engine toe om barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen.

Waarde: Staat de engine toe onjuiste barcodes te herkennen.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt.

Waarde: Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen.

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


Modus die extra herkenning van kleur‑barcodes op kleurafbeeldingen in- of uitschakelt.

Waarde: Extra herkenning van kleur‑barcodes op kleurafbeeldingen.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een afbeelding kan herstellen die is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, tijdens het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die de afbeelding corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherping of wiskundige morfologie.

Waarde: Deconvolutie‑modus die het niveau van beelddegradatie definieert.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance herkenningskwaliteits‑preset. Barcodes van hoge kwaliteit worden goed herkend in deze modus.

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

Waarde: HighPerformance herkenningskwaliteits‑preset.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren.

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

Waarde: HighQuality herkenningskwaliteitsvoorinstelling.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Staat toe de afbeelding te schalen met de specifieke ImageScaleMode

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

Waarde: Extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes.

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

Waarde: MaxQuality herkenningskwaliteitsvoorinstelling.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

Waarde: Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality herkenningskwaliteitsvoorinstelling. Geschikt voor de meeste barcodes

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

Waarde: NormalQuality herkenningskwaliteitsvoorinstelling.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk.

Waarde: grootte (van 1 tot oneindig) van het minimale barcode‑element: matrixcel of balk.

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


Staat de engine toe om barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen.

Waarde: Staat de engine toe onjuiste barcodes te herkennen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt.

Waarde: Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Modus die extra herkenning van kleur‑barcodes op kleurafbeeldingen in- of uitschakelt.

Waarde: Extra herkenning van kleur‑barcodes op kleurafbeeldingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een afbeelding kan herstellen die is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, tijdens het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die de afbeelding corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherping of wiskundige morfologie.

Waarde: Deconvolutie‑modus die het niveau van beelddegradatie definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Staat toe de afbeelding te schalen met de specifieke ImageScaleMode Waarde:

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode waarde |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

Waarde: Extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

Waarde: Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk.

Waarde: grootte (van 1 tot oneindig) van het minimale barcode‑element: matrixcel of balk.

**Parameters:**
| Parameter | Type | Beschrijving |
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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

