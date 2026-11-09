---
title: "QualitySettings"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento."
type: docs
weight: 40
url: /it/java/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object
```
public final class QualitySettings
```

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings con i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxQuality oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

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
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | Consente al motore di riconoscere i codici a barre che hanno un checksumm errato o valori incorretti. |
| [getBarcodeQuality()](#getBarcodeQuality--) | Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| [getDeconvolution()](#getDeconvolution--) | Modalità di deconvoluzione (restaurazione delle immagini) che definisce il livello di degradazione dell'immagine. |
| [getHighPerformance()](#getHighPerformance--) | Preset di qualità di riconoscimento HighPerformance. |
| [getHighQuality()](#getHighQuality--) | Preset di qualità di riconoscimento HighQuality. |
| [getInverseImage()](#getInverseImage--) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza). |
| [getMaxQuality()](#getMaxQuality--) | Preset di qualità di riconoscimento MaxQuality. |
| [getMinimalXDimension()](#getMinimalXDimension--) | Dimensione minima di XDimension in pixel utilizzata con UseMinimalXDimension. |
| [getNormalQuality()](#getNormalQuality--) | Preset di qualità di riconoscimento NormalQuality. |
| [getXDimension()](#getXDimension--) | Modalità di riconoscimento che imposta la dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | Consente al motore di riconoscere i codici a barre che hanno un checksumm errato o valori incorretti. |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori. |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | Modalità di deconvoluzione (restaurazione delle immagini) che definisce il livello di degradazione dell'immagine. |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza). |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | Dimensione minima di XDimension in pixel utilizzata con UseMinimalXDimension. |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | Modalità di riconoscimento che imposta la dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


Consente al motore di riconoscere i codici a barre che hanno un checksumm errato o valori incorretti. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato.

Valore: Consente al motore di riconoscere codici a barre errati.

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

Valore: Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata.

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


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

Valore: Riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Modalità di deconvoluzione (restaurazione delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale, come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che la corrompe, dobbiamo verificare le funzioni più conosciute, come la nitidezza o la morfologia matematica.

Valore: modalità di deconvoluzione che definisce il livello di degradazione dell'immagine.

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità.

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

Valore: preset di qualità di riconoscimento HighPerformance.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


Preset di qualità di riconoscimento HighQuality. Questo preset è sviluppato per codici a barre di bassa qualità. Consente di rilevare codici a barre altamente danneggiati.

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

Valore: preset di qualità di riconoscimento HighQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza).

Valore: riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i codici a barre possibili, anche quelli errati.

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

Valore: preset di qualità di riconoscimento MaxQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


Dimensione minima di XDimension in pixel utilizzata con UseMinimalXDimension.

Valore: dimensione minima di XDimension in pixel che viene usata con UseMinimalXDimension.

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre

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

Valore: preset di qualità di riconoscimento NormalQuality.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


Modalità di riconoscimento che imposta la dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

Valore: dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

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


Consente al motore di riconoscere i codici a barre che hanno un checksumm errato o valori incorretti. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato.

Valore: Consente al motore di riconoscere codici a barre errati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

Valore: Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

Valore: Riconoscimento aggiuntivo di codici a barre a colori su immagini a colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Modalità di deconvoluzione (restaurazione delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale, come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione dell'immagine che la corrompe, dobbiamo verificare le funzioni più conosciute, come la nitidezza o la morfologia matematica.

Valore: modalità di deconvoluzione che definisce il livello di degradazione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


Modalità che abilita o disabilita il riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti (luminanza).

Valore: riconoscimento aggiuntivo di codici a barre su immagini con colori invertiti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


Dimensione minima di XDimension in pixel utilizzata con UseMinimalXDimension.

Valore: dimensione minima di XDimension in pixel che viene usata con UseMinimalXDimension.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


Modalità di riconoscimento che imposta la dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

Valore: dimensione (da 1 a infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

