---
title: "BarCodeReader"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa kode batang, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi kode batang."
type: docs
weight: 14
url: /id/java/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode.

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader  dengan nilai default. |
| [BarCodeReader(BufferedImage image)](#BarCodeReader-java.awt.image.BufferedImage-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader  dari sebuah gambar. |
| [BarCodeReader(BufferedImage image, BaseDecodeType decodeType)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)](#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)](#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader  dari file. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi sebuah instance baru dari kelas  BarCodeReader . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [abort()](#abort--) | Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | Mengekspor properti BarCode ke xml-stream yang ditentukan |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Mengekspor properti BarCode ke xml-file yang ditentukan |
| [getBarCodeReadType()](#getBarCodeReadType--) | Mendapatkan tipe decode dari decoding kode batang input |
| [getBarcodeSettings()](#getBarcodeSettings--) | Parameter dekoding BarCode utama. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | Mendapatkan array BarCodeResult yang dikenali |
| [getFoundCount()](#getFoundCount--) | Mendapatkan jumlah barcodes yang dikenali |
| [getProcessorSettings()](#getProcessorSettings--) | Mendapatkan pengaturan penggunaan inti prosesor. |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings memungkinkan konfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [getTimeout()](#getTimeout--) | Mendapatkan batas waktu proses pengenalan dalam milidetik. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | Mengimpor properti BarCode dari xml-stream yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Mengimpor properti BarCode dari xml-file yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | Membaca BarCodeResult s dari gambar. |
| [setBarCodeImage(BufferedImage value)](#setBarCodeImage-java.awt.image.BufferedImage-) | Mengatur gambar bitmap untuk pengenalan. |
| [setBarCodeImage(BufferedImage value, Rectangle area)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-) | Mengatur gambar bitmap dan area untuk pengenalan. |
| [setBarCodeImage(BufferedImage value, Rectangle[] areas)](#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---) | Mengatur gambar bitmap dan area-area untuk pengenalan. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | Mengatur aliran gambar untuk pengenalan. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | Mengatur berkas gambar untuk pengenalan. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Mengatur tipe decode untuk pengenalan. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Mengatur array tipe SingleDecodeType untuk pengenalan. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings memungkinkan konfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [setTimeout(int value)](#setTimeout-int-) | Mengatur batas waktu proses pengenalan dalam milidetik. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


Menginisialisasi instance baru kelas BarCodeReader dengan nilai default. Memerlukan penetapan gambar (SetBitmapImage()) sebelum memanggil metode ReadBarCodes().

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


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader  dari sebuah gambar.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | Sebuah instance Bitmap yang berisi gambar |

### BarCodeReader(BufferedImage image, BaseDecodeType decodeType) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType decodeType)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | Gambar. |
| decodeType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode1. Bisa tunggal atau banyak |

### BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, BaseDecodeType[] decodeTypes)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | Gambar. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode. |

### BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(BufferedImage image, Rectangle area, BaseDecodeType[] decodeTypes)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | Gambar. |
| area | java.awt.Rectangle | Area untuk pengenalan. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode. |

### BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle[] areas, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Jalur gambar. |
| area | java.awt.Rectangle[] | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle area, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran gambar. |
| area | java.awt.Rectangle | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type) {#BarCodeReader-java.lang.String-java.awt.Rectangle-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rectangle area, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Jalur gambar. |
| area | java.awt.Rectangle | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rectangle[] areas, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran gambar. |
| area | java.awt.Rectangle[] | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type) {#BarCodeReader-java.awt.image.BufferedImage-java.awt.Rectangle---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(BufferedImage image, Rectangle[] areas, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | Gambar. |
| area | java.awt.Rectangle[] | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader  dari file.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Jenis dekode. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


Menginisialisasi sebuah instance baru dari kelas  BarCodeReader .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe decode. |

### abort() {#abort--}
```
public void abort()
```


Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. Metode ini harus digunakan ketika proses pengenalan terlalu lama.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xmlStream) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xmlStream)
```


Mengekspor properti BarCode ke xml-stream yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | xml-stream untuk menyimpan |

**Returns:**
boolean - Apakah ekspor selesai dengan sukses atau tidak.

Mengembalikan **True**  jika berhasil;  **False**  jika tidak.
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Mengekspor properti BarCode ke xml-file yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFile | java.lang.String | Nama file |

**Returns:**
boolean - Apakah ekspor selesai dengan sukses atau tidak.

Mengembalikan **True**  jika berhasil;  **False**  jika tidak.
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


Mendapatkan tipe decode dari decoding kode batang input

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


Parameter dekode BarCode utama. Berisi parameter yang memengaruhi data yang dikenali.

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


Mendapatkan array BarCodeResult yang dikenali

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

Nilai: Array BarCodeResult yang dikenali

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


Mendapatkan jumlah barcodes yang dikenali

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

Nilai: Jumlah barcode yang dikenali

**Returns:**
int
### getProcessorSettings() {#getProcessorSettings--}
```
public static ProcessorSettings getProcessorSettings()
```


Mendapatkan pengaturan penggunaan inti prosesor.

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


QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

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

Nilai: QualitySettings untuk mengkonfigurasi kualitas dan kecepatan pengenalan.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Mendapatkan batas waktu proses pengenalan dalam milidetik.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
     reader.setTimeout(5000);
     for(BarCodeResult result : reader.readBarCodes())
         System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Returns:**
int - Batas waktu.
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


Mengimpor properti BarCode dari xml-stream yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlStream | java.io.InputStream | Aliran xml untuk memuat |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


Mengimpor properti BarCode dari xml-file yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFile | java.lang.String | Nama file |

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


Membaca BarCodeResult s dari gambar.

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
com.aspose.barcode.barcoderecognition.BarCodeResult[] - Mengembalikan array dari BarCodeResult yang dikenali pada gambar. Jika tidak ada yang dikenali, array nol dikembalikan.
### setBarCodeImage(BufferedImage value) {#setBarCodeImage-java.awt.image.BufferedImage-}
```
public void setBarCodeImage(BufferedImage value)
```


Mengatur gambar bitmap untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | Gambar bitmap untuk pengenalan. |

### setBarCodeImage(BufferedImage value, Rectangle area) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle-}
```
public final void setBarCodeImage(BufferedImage value, Rectangle area)
```


Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | Gambar bitmap untuk pengenalan. |
| area | java.awt.Rectangle | area untuk pengenalan |

### setBarCodeImage(BufferedImage value, Rectangle[] areas) {#setBarCodeImage-java.awt.image.BufferedImage-java.awt.Rectangle---}
```
public final void setBarCodeImage(BufferedImage value, Rectangle[] areas)
```


Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | Gambar bitmap untuk pengenalan. |
| area | java.awt.Rectangle[] | daftar area untuk pengenalan |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Mengatur aliran gambar untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.InputStream | Aliran gambar untuk pengenalan. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


Mengatur berkas gambar untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Berkas gambar untuk pengenalan. |

### setBarCodeReadType(BaseDecodeType type) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarCodeReadType(BaseDecodeType type)
```


Mengatur tipe decode untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe barcode yang akan dibaca. |

### setBarCodeReadType(SingleDecodeType[] barcodeTypes) {#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public void setBarCodeReadType(SingleDecodeType[] barcodeTypes)
```


Mengatur array tipe SingleDecodeType untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Array tipe SingleDecodeType untuk dibaca. |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public final void setQualitySettings(QualitySettings value)
```


QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

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

Nilai: QualitySettings untuk mengkonfigurasi kualitas dan kecepatan pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Mengatur batas waktu proses pengenalan dalam milidetik.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Batas waktu. |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

