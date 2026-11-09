---
title: "BarCodeReader"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre; può quindi eseguire l'operazione ReadBarCodes per rilevare i codici a barre."
type: docs
weight: 14
url: /it/java/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | Inizializza una nuova istanza della classe  BarCodeReader  con valori predefiniti. |
| [BarCodeReader(BufferedImage image)](#BarCodeReader-java.awt.image.BufferedImage-) | Inizializza una nuova istanza della classe  BarCodeReader  da un'immagine. |
| [BarCodeReader(BufferedImage image, BaseDecodeType decodeType)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | Inizializza una nuova istanza della classe  BarCodeReader  da file. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Inizializza una nuova istanza della classe  BarCodeReader  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [abort()](#abort--) | La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | Esporta le proprietà BarCode nello stream xml specificato |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Esporta le proprietà BarCode nel file xml specificato |
| [getBarCodeReadType()](#getBarCodeReadType--) | Ottiene il tipo di decodifica del barcode di input |
| [getBarcodeSettings()](#getBarcodeSettings--) | I principali parametri di decodifica del BarCode. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | Ottiene l'array di  BarCodeResult s riconosciuti |
| [getFoundCount()](#getFoundCount--) | Ottiene il conteggio dei codici a barre riconosciuti |
| [getProcessorSettings()](#getProcessorSettings--) | Ottiene le impostazioni per l'uso dei core del processore. |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. |
| [getTimeout()](#getTimeout--) | Ottiene il timeout del processo di riconoscimento in millisecondi. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | Importa le proprietà BarCode dallo stream XML specificato e le applica all'istanza corrente di BarCodeReader. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Importa le proprietà BarCode dal file XML specificato e le applica all'istanza corrente di BarCodeReader. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | Legge i BarCodeResult dall'immagine. |
| [setBarCodeImage(BufferedImage value)](#setBarCodeImage-java.awt.image.BufferedImage-) | Imposta l'immagine bitmap per il riconoscimento. |
| [setBarCodeImage(BufferedImage value, Rectangle area)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-) | Imposta l'immagine bitmap e l'area per il riconoscimento. |
| [setBarCodeImage(BufferedImage value, Rectangle[] areas)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---) | Imposta l'immagine bitmap e le aree per il riconoscimento. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | Imposta lo stream dell'immagine per il riconoscimento. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | Imposta il file immagine per il riconoscimento. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Imposta il tipo di decodifica per il riconoscimento. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Imposta l'array di tipo SingleDecodeType per il riconoscimento. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. |
| [setTimeout(int value)](#setTimeout-int-) | Imposta il timeout del processo di riconoscimento in millisecondi. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


Inizializza una nuova istanza della classe BarCodeReader con valori predefiniti. È necessario impostare l'immagine (SetBitmapImage()) prima di chiamare il metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("c:\\test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

### BarCodeReader(BufferedImage image) {#BarCodeReader-java.awt.image.BufferedImage-}
```
public BarCodeReader(BufferedImage image)
```


Inizializza una nuova istanza della classe  BarCodeReader  da un'immagine.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | Un'istanza Bitmap contenente l'immagine |

### BarCodeReader(BufferedImage image, BaseDecodeType decodeType) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType decodeType)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | L'immagine. |
| decodeType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica type1. Può essere singolo o multiplo. |

### BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | L'immagine. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi di decodifica. |

### BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | L'immagine. |
| area | java.awt.Rectangle | L'area per il riconoscimento. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi di decodifica. |

### BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imagePath | java.lang.String | Il percorso dell'immagine. |
| aree | java.awt.Rectangle[] | L'area per il riconoscimento. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso dell'immagine. |
| area | java.awt.Rectangle | L'area per il riconoscimento. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imagePath | java.lang.String | Il percorso dell'immagine. |
| area | java.awt.Rectangle | L'area per il riconoscimento. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso dell'immagine. |
| aree | java.awt.Rectangle[] | L'area per il riconoscimento. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | java.awt.image.BufferedImage | L'immagine. |
| aree | java.awt.Rectangle[] | L'area per il riconoscimento. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


Inizializza una nuova istanza della classe  BarCodeReader  da file.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png");
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi di decodifica. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di decodifica. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


Inizializza una nuova istanza della classe  BarCodeReader  .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipi di decodifica. |

### abort() {#abort--}
```
public void abort()
```


La funzione richiede la terminazione della sessione di riconoscimento corrente da un altro thread. Abort è un metodo non bloccabile e restituisce il controllo subito dopo la chiamata. Il metodo dovrebbe essere usato quando il processo di riconoscimento è troppo lungo.

--------------------

> ```
> This sample shows how to call Abort function from other thread
>  
>   final BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>   Thread thread1 = new Thread(new Runnable()
>   {
>       public void run()
>       {
>           for(BarCodeResult result : reader.readBarCodes())
>           {
>               System.out.println("BarCode Type: " + result.getCodeType());
>               System.out.println("BarCode CodeText: " + result.getCodeText());
>           }
>        }
>   });
>   thread1.start();
>   Thread.sleep(100);
>   reader.abort();
> ```

### dispose() {#dispose--}
```
public void dispose()
```




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
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


Esporta le proprietà BarCode nello stream xml specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | Il xml-stream per il salvataggio |

**Returns:**
boolean - Indica se l'esportazione è stata completata con successo o meno.

Restituisce  **True**  in caso di successo;  **False**  altrimenti
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Esporta le proprietà BarCode nel file xml specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFile | java.lang.String | Il nome del file |

**Returns:**
boolean - Indica se l'esportazione è stata completata con successo o meno.

Restituisce  **True**  in caso di successo;  **False**  altrimenti
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


Ottiene il tipo di decodifica del barcode di input

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


I principali parametri di decodifica del BarCode. Contiene parametri che influenzano i dati riconosciuti.

**Returns:**
[BarcodeSettings](../../com.aspose.barcode.barcoderecognition/barcodesettings) - The main BarCode decoding parameters
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFoundBarCodes() {#getFoundBarCodes--}
```
public BarCodeResult[] getFoundBarCodes()
```


Ottiene l'array di  BarCodeResult s riconosciuti

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  {
>      reader.readBarCodes();
>      for(int i = 0; reader.getFoundCount() > i; ++i)
>          System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
>  }
> ```

Valore: L'array di BarCodeResult riconosciuti

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


Ottiene il conteggio dei codici a barre riconosciuti

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

Valore: Il conteggio dei codici a barre riconosciuti

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


Ottiene le impostazioni per l'uso dei core del processore.

--------------------

> ```
> This sample shows how to use ProcessorSettings to add maximum multi-threaded performnce
>  
>  //this allows to use all cores for single BarCodeReader call
>  BarCodeReader.getProcessorSettings().setUseAllCores(true);
>  //this allows to use current count of cores
>  BarCodeReader.getProcessorSettings().setUseAllCores(false);
>  BarCodeReader.getProcessorSettings().setUseOnlyThisCoresCount(Math.max(1, Environment.getProcessorCount() / 2));
> ```

**Returns:**
[ProcessorSettings](../../com.aspose.barcode.barcoderecognition/processorsettings)
### getQualitySettings() {#getQualitySettings--}
```
public final QualitySettings getQualitySettings()
```


QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Valore: QualitySettings per configurare la qualità e la velocità del riconoscimento.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Ottiene il timeout del processo di riconoscimento in millisecondi.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - Il timeout.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xmlStream) {#importFromXml-java.io.InputStream-}
```
public static BarCodeReader importFromXml(InputStream xmlStream)
```


Importa le proprietà BarCode dallo stream XML specificato e le applica all'istanza corrente di BarCodeReader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlStream | java.io.InputStream | Il flusso xml per il caricamento |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


Importa le proprietà BarCode dal file XML specificato e le applica all'istanza corrente di BarCodeReader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFile | java.lang.String | Il nome del file |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readBarCodes() {#readBarCodes--}
```
public BarCodeResult[] readBarCodes()
```


Legge i BarCodeResult dall'immagine.

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[] - Restituisce un array di BarCodeResult riconosciuti nell'immagine. Se non viene riconosciuto nulla, viene restituito un array vuoto.
### setBarCodeImage(BufferedImage value) {#setBarCodeImage-java.awt.image.BufferedImage-}
```
public void setBarCodeImage(BufferedImage value)
```


Imposta l'immagine bitmap per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage(bmp);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.image.BufferedImage | L'immagine bitmap per il riconoscimento. |

### setBarCodeImage(BufferedImage value, Rectangle area) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-}
```
public final void setBarCodeImage(BufferedImage value, Rectangle area)
```


Imposta l'immagine bitmap e l'area per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()));
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.image.BufferedImage | L'immagine bitmap per il riconoscimento. |
| area | java.awt.Rectangle | area per il riconoscimento |

### setBarCodeImage(BufferedImage value, Rectangle[] areas) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---}
```
public final void setBarCodeImage(BufferedImage value, Rectangle[] areas)
```


Imposta l'immagine bitmap e le aree per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BufferedImage bmp = ImageIO.read(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()) });
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.image.BufferedImage | L'immagine bitmap per il riconoscimento. |
| aree | java.awt.Rectangle[] | elenco delle aree per il riconoscimento |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Imposta lo stream dell'immagine per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("c:\\test.png"));
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage(fstr);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Lo stream dell'immagine per il riconoscimento. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


Imposta il file immagine per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage("c:\\test.png");
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il file immagine per il riconoscimento. |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


Imposta il tipo di decodifica per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128));
>  reader.setBarCodeImage("c:/test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
>  System.out.println("BarCodeReadType: " + reader.getBarCodeReadType().toString());
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il tipo di codice a barre da leggere. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Imposta l'array di tipo SingleDecodeType per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("c:\\test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | L'array di tipo SingleDecodeType da leggere. |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Valore: QualitySettings per configurare la qualità e la velocità del riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Imposta il timeout del processo di riconoscimento in millisecondi.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il timeout. |

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

