---
title: BarCodeReader
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode.
type: docs
weight: 15
url: /id/androidjava/com.aspose.barcode.barcoderecognition/barcodereader/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReader
```

BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa kode batang, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi kode batang.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [BarCodeReader()](#BarCodeReader--) | Menginisialisasi instance baru dari kelas  BarCodeReader  dengan nilai default. |
| [BarCodeReader(Bitmap image)](#BarCodeReader-android.graphics.Bitmap-) | Menginisialisasi instance baru dari kelas  BarCodeReader  dari sebuah gambar. |
| [BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(Bitmap image, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String imagePath, Rect area, BaseDecodeType type)](#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)](#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [BarCodeReader(String filename)](#BarCodeReader-java.lang.String-) | Menginisialisasi instance baru dari kelas  BarCodeReader  dari file. |
| [BarCodeReader(String filename, BaseDecodeType type)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(String filename, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream)](#BarCodeReader-java.io.InputStream-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType type)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
| [BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)](#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Menginisialisasi instance baru dari kelas  BarCodeReader . |
## Methods

| Method | Deskripsi |
| --- | --- |
| [abort()](#abort--) | Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xmlStream)](#exportToXml-java.io.OutputStream-) | Mengekspor properti BarCode ke xml-stream yang ditentukan |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Mengekspor properti BarCode ke xml-file yang ditentukan |
| [getBarCodeReadType()](#getBarCodeReadType--) | Mengambil tipe dekode dari decoding barcode input |
| [getBarcodeSettings()](#getBarcodeSettings--) | Parameter dekode BarCode utama. |
| [getClass()](#getClass--) |  |
| [getFoundBarCodes()](#getFoundBarCodes--) | Mengambil array BarCodeResult yang dikenali |
| [getFoundCount()](#getFoundCount--) | Mengambil jumlah barcode yang dikenali |
| [getProcessorSettings()](#getProcessorSettings--) | Mengambil pengaturan penggunaan core prosesor. |
| [getQualitySettings()](#getQualitySettings--) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [getTimeout()](#getTimeout--) | Mendapatkan batas waktu proses pengenalan dalam milidetik. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xmlStream)](#importFromXml-java.io.InputStream-) | Mengimpor properti BarCode dari xml-stream yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Mengimpor properti BarCode dari file xml yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBarCodes()](#readBarCodes--) | Membaca BarCodeResult s dari gambar. |
| [setBarCodeImage(Bitmap value)](#setBarCodeImage-android.graphics.Bitmap-) | Mengatur gambar bitmap untuk pengenalan. |
| [setBarCodeImage(Bitmap value, Rect area)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-) | Mengatur gambar bitmap dan area untuk pengenalan. |
| [setBarCodeImage(Bitmap value, Rect[] areas)](#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---) | Mengatur gambar bitmap dan area-area untuk pengenalan. |
| [setBarCodeImage(InputStream stream)](#setBarCodeImage-java.io.InputStream-) | Mengatur aliran gambar untuk pengenalan. |
| [setBarCodeImage(String filename)](#setBarCodeImage-java.lang.String-) | Mengatur file gambar untuk pengenalan. |
| [setBarCodeReadType(BaseDecodeType type)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Mengatur tipe decode untuk pengenalan. |
| [setBarCodeReadType(SingleDecodeType[] barcodeTypes)](#setBarCodeReadType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Mengatur array tipe SingleDecodeType untuk pengenalan. |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [setTimeout(int value)](#setTimeout-int-) | Mengatur batas waktu proses pengenalan dalam milidetik. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReader() {#BarCodeReader--}
```
public BarCodeReader()
```


Menginisialisasi instance baru dari kelas  BarCodeReader  dengan nilai default. Memerlukan pengaturan gambar (SetBitmapImage()) sebelum memanggil metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader();
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

### BarCodeReader(Bitmap image) {#BarCodeReader-android.graphics.Bitmap-}
```
public BarCodeReader(Bitmap image)
```


Menginisialisasi instance baru dari kelas  BarCodeReader  dari sebuah gambar.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap | Instance Bitmap yang berisi gambar |

### BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, BaseDecodeType[] decodeTypes)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap | Gambar. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(Bitmap image, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap | Gambar. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode type1. Bisa tunggal atau ganda. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType[] decodeTypes)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap | Gambar. |
| area | android.graphics.Rect | Area untuk pengenalan. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect[] areas, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Path gambar. |
| areas | android.graphics.Rect[] | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(InputStream stream, Rect area, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect area, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran gambar. |
| area | android.graphics.Rect | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(String imagePath, Rect area, BaseDecodeType type) {#BarCodeReader-java.lang.String-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String imagePath, Rect area, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| imagePath | java.lang.String | Path gambar. |
| area | android.graphics.Rect | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, Rect[] areas, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran gambar. |
| areas | android.graphics.Rect[] | Area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect---com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect[] areas, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
>  BarCodeReader reader = new BarCodeReader(bmp, new Rectangle(0, 0, bmp.getWidth(), bmp.getHeight()), new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap | Gambar. |
| areas | android.graphics.Rect[] | Area-area untuk pengenalan. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(Bitmap image, Rect area, BaseDecodeType type) {#BarCodeReader-android.graphics.Bitmap-android.graphics.Rect-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(Bitmap image, Rect area, BaseDecodeType type)
```


**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| gambar | android.graphics.Bitmap |  |
| area | android.graphics.Rect |  |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### BarCodeReader(String filename) {#BarCodeReader-java.lang.String-}
```
public BarCodeReader(String filename)
```


Menginisialisasi instance baru dari kelas  BarCodeReader  dari file.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png");
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |

### BarCodeReader(String filename, BaseDecodeType type) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(String filename, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(String filename, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.lang.String-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(String filename, BaseDecodeType[] decodeTypes)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Nama file. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(InputStream stream) {#BarCodeReader-java.io.InputStream-}
```
public BarCodeReader(InputStream stream)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr);
>  reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran. |

### BarCodeReader(InputStream stream, BaseDecodeType type) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public BarCodeReader(InputStream stream, BaseDecodeType type)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("test.png");
>  BarCodeReader reader = new BarCodeReader(fstr, new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran. |
| type | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes) {#BarCodeReader-java.io.InputStream-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public BarCodeReader(InputStream stream, BaseDecodeType[] decodeTypes)
```


Menginisialisasi instance baru dari kelas  BarCodeReader .

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream("test.png"));
>  BarCodeReader reader = new BarCodeReader(fstr, DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran. |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tipe dekode. |

### abort() {#abort--}
```
public void abort()
```


Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. Metode ini harus digunakan ketika proses pengenalan terlalu lama.

--------------------

> ```
> This sample shows how to call Abort function from other thread
>  
>   final BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>   Thread thread1 = new Thread(new Runnable()
>   {
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| xmlStream | java.io.OutputStream | xml-stream untuk penyimpanan |

**Returns:**
boolean - Apakah ekspor selesai dengan sukses atau tidak.

Mengembalikan  **True**  jika berhasil;  **False**  Jika tidak
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


Mengekspor properti BarCode ke xml-file yang ditentukan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| xmlFile | java.lang.String | Nama file |

**Returns:**
boolean - Apakah ekspor selesai dengan sukses atau tidak.

Mengembalikan  **True**  jika berhasil;  **False**  Jika tidak
### getBarCodeReadType() {#getBarCodeReadType--}
```
public BaseDecodeType getBarCodeReadType()
```


Mengambil tipe dekode dari decoding barcode input

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getBarcodeSettings() {#getBarcodeSettings--}
```
public BarcodeSettings getBarcodeSettings()
```


Parameter utama untuk decoding BarCode. Berisi parameter yang memengaruhi data yang dikenali.

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


Mengambil array BarCodeResult yang dikenali

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  {
>      reader.readBarCodes();
>      for(int i = 0; reader.getFoundCount() > i; ++i)
>          System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
>  }
> ```

Nilai: Array BarCodeResult s yang dikenali

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### getFoundCount() {#getFoundCount--}
```
public int getFoundCount()
```


Mengambil jumlah barcode yang dikenali

--------------------

> ```
> This sample shows how to read barcodes with BarCodeReader
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
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


Mengambil pengaturan penggunaan core prosesor.

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
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Nilai: QualitySettings untuk mengatur kualitas dan kecepatan pengenalan.

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public int getTimeout()
```


Mendapatkan batas waktu proses pengenalan dalam milidetik.

```
BarCodeReader reader = new BarCodeReader("test.png");
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| xmlStream | java.io.InputStream | xml-stream untuk memuat |

**Returns:**
[BarCodeReader](../../com.aspose.barcode.barcoderecognition/barcodereader) - Returns  **True**  in case of success;

 **False**  Otherwise
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarCodeReader importFromXml(String xmlFile)
```


Mengimpor properti BarCode dari file xml yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini.

**Parameters:**
| Parameter | Type | Deskripsi |
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
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.readBarCodes();
>  for(int i = 0; reader.getFoundCount() > i; ++i)
>     System.out.println("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
> ```

**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[] - Mengembalikan array BarCodeResult s yang dikenali pada gambar. Jika tidak ada yang dikenali, array kosong dikembalikan.
### setBarCodeImage(Bitmap value) {#setBarCodeImage-android.graphics.Bitmap-}
```
public void setBarCodeImage(Bitmap value)
```


Mengatur gambar bitmap untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Bitmap | Gambar bitmap untuk pengenalan. |

### setBarCodeImage(Bitmap value, Rect area) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect-}
```
public final void setBarCodeImage(Bitmap value, Rect area)
```


Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Bitmap | Gambar bitmap untuk pengenalan. |
| area | android.graphics.Rect | area untuk pengenalan |

### setBarCodeImage(Bitmap value, Rect[] areas) {#setBarCodeImage-android.graphics.Bitmap-android.graphics.Rect---}
```
public final void setBarCodeImage(Bitmap value, Rect[] areas)
```


Mengatur gambar bitmap dan area-area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  Bitmap bmp = BitmapFactory.decodeFile("test.png");
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | android.graphics.Bitmap | Gambar bitmap untuk pengenalan. |
| areas | android.graphics.Rect[] | daftar area untuk pengenalan |

### setBarCodeImage(InputStream stream) {#setBarCodeImage-java.io.InputStream-}
```
public final void setBarCodeImage(InputStream stream)
```


Mengatur aliran gambar untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  InputStream fstr = new FileInputStream(new File("test.png"));
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran gambar untuk pengenalan. |

### setBarCodeImage(String filename) {#setBarCodeImage-java.lang.String-}
```
public void setBarCodeImage(String filename)
```


Mengatur file gambar untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes().

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader())
>  {
>      reader.setBarCodeReadType(DecodeType.CODE_39, DecodeType.CODE_128);
>      reader.setBarCodeImage("test.png");
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>      }
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | File gambar untuk pengenalan. |

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
>  reader.setBarCodeReadType(new MultiDecodeType(DecodeType.CODE_39, DecodeType.CODE_128);
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
>  System.out.println("BarCodeReadType: " + reader.getBarCodeReadType().toString());
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
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
>  reader.setBarCodeImage("test.png");
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```

**Parameters:**
| Parameter | Type | Deskripsi |
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
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //normal quality mode is set by default
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  //set high performance mode
>  reader.setQualitySettings(QualitySettings.getHighPerformance());
>  //set separate options
>  reader.getQualitySettings().setAllowMedianSmoothing(true);
>  reader.getQualitySettings().setMedianSmoothingWindowSize(5);
>  for(BarCodeResult result : reader.readBarCodes())
>    System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

Nilai: QualitySettings untuk mengatur kualitas dan kecepatan pengenalan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public void setTimeout(int value)
```


Mengatur batas waktu proses pengenalan dalam milidetik.

```
BarCodeReader reader = new BarCodeReader("test.png");
 reader.setTimeout(5000);
 for(BarCodeResult result : reader.readBarCodes())
    System.out.println("BarCode CodeText: " + result.getCodeText());
```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | Batas waktu. |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

