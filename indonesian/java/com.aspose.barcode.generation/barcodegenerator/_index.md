---
title: "BarcodeGenerator"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "BarcodeGenerator untuk pembuatan gambar barcode backend."
type: docs
weight: 13
url: /id/java/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator untuk pembuatan gambar barcode backend.

simbol yang didukung: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | Membuat sebuah instance dari BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | Membuat sebuah instance dari BarcodeGenerator. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Bersihkan semua sumber daya yang sedang digunakan. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | Mengekspor properti BarCode ke xml-stream yang ditentukan |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | Mengekspor properti BarCode ke xml-file yang ditentukan |
| [generateBarCodeImage()](#generateBarCodeImage--) | Hasilkan gambar barcode dengan pengaturan saat ini. |
| [getBarcodeType()](#getBarcodeType--) | Tipe simbol barcode. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | Teks yang akan dienkode. |
| [getParameters()](#getParameters--) | Parameter generasi. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | Mengimpor properti BarCode dari xml-stream yang ditentukan dan membuat instance BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | Mengimpor properti BarCode dari xml-file yang ditentukan dan membuat instance BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Simpan gambar barcode ke stream dalam format tertentu. |
| [save(String filename)](#save-java.lang.String-) | Simpan gambar barcode ke file tertentu. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Simpan gambar barcode ke file tertentu dalam format tertentu. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Tipe simbol barcode. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | Atur codetext sebagai urutan byte. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | Teks yang akan dienkode. |
| [setCodeText(String codeText, Charset encoding)](#setCodeText-java.lang.String-java.nio.charset.Charset-) |  |
| [setCodeText(String codeText, Charset encoding, boolean insertBOM)](#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGenerator(BaseEncodeType type) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-}
```
public BarcodeGenerator(BaseEncodeType type)
```


Membuat sebuah instance dari BarcodeGenerator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipe simbol barcode. Gunakan kelas  EncodeTypes  untuk menyiapkan simbol. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


Membuat sebuah instance dari BarcodeGenerator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | Tipe simbol barcode. Gunakan kelas  EncodeTypes  untuk menyiapkan simbol. |
| codeText | java.lang.String | Teks yang akan dienkode. |

### dispose() {#dispose--}
```
public void dispose()
```


Bersihkan semua sumber daya yang sedang digunakan.

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
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


Mengekspor properti BarCode ke xml-stream yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xml | java.io.OutputStream | xml-stream |

**Returns:**
boolean - Apakah ekspor selesai dengan sukses atau tidak. Mengembalikan **True** jika berhasil; **False** jika tidak.
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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Hasilkan gambar barcode dengan pengaturan saat ini.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          BufferedImage image = generator.generateBarCodeImage();
>          ImageIO.write(image, "png",outputFile);
> ```

**Returns:**
java.awt.image.BufferedImage - Gambar barcode. Lihat Bitmap.
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Tipe simbol barcode.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Teks yang akan dienkode.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Parameter generasi.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importFromXml(InputStream xml) {#importFromXml-java.io.InputStream-}
```
public static BarcodeGenerator importFromXml(InputStream xml)
```


Mengimpor properti BarCode dari xml-stream yang ditentukan dan membuat instance BarcodeGenerator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xml | java.io.InputStream | xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


Mengimpor properti BarCode dari xml-file yang ditentukan dan membuat instance BarcodeGenerator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFile | java.lang.String | Nama file |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Simpan gambar barcode ke stream dalam format tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | java.io.OutputStream | Output OutputStream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Menentukan format file dari gambar keluaran. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Simpan gambar barcode ke file tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Jalur untuk disimpan. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Simpan gambar barcode ke file tertentu dalam format tertentu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama file | java.lang.String | Jalur untuk disimpan. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Menentukan format file dari gambar keluaran. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Tipe simbol barcode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


Atur codetext sebagai urutan byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeBytes | byte[] | Byte dari codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


Teks yang akan dienkode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


Mengkodekan **codeText** Unicode menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya, fungsi secara otomatis menyisipkan sebuah [byte order mark (BOM)][byte order mark _BOM] .

Fungsi ini hanya ditujukan untuk penggunaan barcode 2D (mis., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Fungsi ini memungkinkan pengkodean manual teks Unicode menggunakan encoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, encoding  [ECI][]  direkomendasikan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang sesuai GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` setting Unicode-encoded text for 2D barcodes using different encodings:
>   
>   //Encode QR Code text using UTF-8 with BOM
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8;
>   gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode DataMatrix text using Shift-JIS (Japanese encoding)
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	Charset charset = Charset.forName("Shift_JIS");
>  	gen.setCodeText("\u8eca\u7a2e\u540d", charset);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(charset));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | java.lang.String | String CodeText |
| encoding | java.nio.charset.Charset | Encoding yang diterapkan |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


Mengkodekan **codeText** Unicode menjadi urutan byte menggunakan **encoding** yang ditentukan. UTF-8 adalah encoding yang paling umum digunakan. Jika encoding mendukungnya dan **insertBOM** diatur ke true, fungsi menyertakan sebuah [byte order mark (BOM)][byte order mark _BOM] .

Fungsi ini hanya ditujukan untuk penggunaan barcode 2D (mis., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, dll.). Fungsi ini memungkinkan pengkodean manual teks Unicode menggunakan encoding nasional atau khusus; namun, metode ini dianggap usang dalam aplikasi modern. Untuk kasus penggunaan modern, encoding  [ECI][]  direkomendasikan untuk data Unicode.

Menggunakan fungsi ini dengan barcode 1D, barcode yang sesuai GS1 (termasuk 2D), atau barcode HIBC (termasuk 2D) tidak didukung oleh standar barcode yang bersangkutan dan dapat menghasilkan hasil yang tidak dapat diprediksi.

--------------------

> ```
> This example shows how to use ```
> SetCodeText
> ``` with or without a BOM for 2D barcodes.
>   
>  	//Encode codetext using UTF-8 with BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, true);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> 
>  	//Encode codetext using UTF-8 without BOM
>  	BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR);
>   gen.setCodeText("\u8eca\u7a2e\u540d", StandardCharsets.UTF_8, false);
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR);
>  	for(BarCodeResult result : reader.readBarCodes())
>  	   System.out.println("BarCode CodeText: " + result.getCodeText());
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codeText | java.lang.String | String CodeText |
| encoding | java.nio.charset.Charset | Encoding yang diterapkan |
| insertBOM | boolean | Menunjukkan apakah akan menyisipkan byte order mark (BOM) ketika encoding yang ditentukan mendukungnya (mis., UTF-8, UTF-16, UTF-32). Jika diatur ke true, BOM akan ditambahkan; jika false, BOM akan diabaikan meskipun encoding biasanya menggunakannya. |

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

