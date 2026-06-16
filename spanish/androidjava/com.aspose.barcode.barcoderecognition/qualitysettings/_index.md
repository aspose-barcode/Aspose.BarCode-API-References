---
title: QualitySettings
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento.
type: docs
weight: 44
url: /es/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings con los presets incorporados: HighPerformance, NormalQuality, HighQuality, MaxQuality o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

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

| Constructor | Descripción |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | Constructor de QualitySettings |
## Campos

| Campo | Descripción |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Permite que el motor reconozca códigos de barras que tienen una suma de verificación incorrecta o valores incorrectos. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| [getDeconvolution()](#getDeconvolution--) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. |
| [getHighPerformance()](#getHighPerformance--) | Preset de calidad de reconocimiento HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Preset de calidad de reconocimiento HighQuality. |
| [getImageScalingMode()](#getImageScalingMode--) | Permite escalar la imagen con el modo ImageScaleMode específico. |
| [getInverseImage()](#getInverseImage--) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [getMaxQuality()](#getMaxQuality--) | Preset de calidad de reconocimiento MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Preset de calidad de reconocimiento NormalQuality. |
| [getXDimension()](#getXDimension--) | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Permite que el motor reconozca códigos de barras que tienen una suma de verificación incorrecta o valores incorrectos. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | Permite escalar la imagen con el valor específico del modo ImageScaleMode: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


Constructor de QualitySettings

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Permite que el motor reconozca códigos de barras que tienen una suma de verificación incorrecta o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto.

Valor: Permite que el motor reconozca códigos de barras incorrectos.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

Valor: Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada.

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


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color.

Valor: Reconocimiento adicional de códigos de barras de color en imágenes a color.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, durante la captura de la imagen con la cámara. Como no podemos detectar la función de la imagen que la corrompe, debemos comprobar las funciones más conocidas, como el enfoque o la morfología matemática.

Valor: Modo de deconvolución que define el nivel de degradación de la imagen.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Preset de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo.

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

Valor: Preset de calidad de reconocimiento HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados.

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

Valor: preajuste de calidad de reconocimiento HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


Permite escalar la imagen con el modo ImageScaleMode específico.

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

Valor: reconocimiento adicional de códigos de barras en imágenes con colores inversos

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos.

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

Valor: preajuste de calidad de reconocimiento MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

Valor: tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras

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

Valor: preajuste de calidad de reconocimiento NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

Valor: tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

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


Permite que el motor reconozca códigos de barras que tienen una suma de verificación incorrecta o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto.

Valor: Permite que el motor reconozca códigos de barras incorrectos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

Valor: Modo que habilita los métodos para reconocer elementos de códigos de barras con la calidad seleccionada.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color.

Valor: Reconocimiento adicional de códigos de barras de color en imágenes a color.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, durante la captura de la imagen con la cámara. Como no podemos detectar la función de la imagen que la corrompe, debemos comprobar las funciones más conocidas, como el enfoque o la morfología matemática.

Valor: Modo de deconvolución que define el nivel de degradación de la imagen.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


Permite escalar la imagen con el valor específico del modo ImageScaleMode:

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | com.aspose.barcode.barcoderecognition.ImageScalingMode | valor ImageScalingMode |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

Valor: reconocimiento adicional de códigos de barras en imágenes con colores inversos

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

Valor: tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

Valor: tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

**Parameters:**
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

