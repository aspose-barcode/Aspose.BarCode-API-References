---
title: BarcodeGenerator
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: BarcodeGenerator لتوليد صور الباركود الخلفية.
type: docs
weight: 13
url: /ar/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

BarcodeGenerator لتوليد صور الباركود الخلفية.

الرموز المدعومة: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | ينشئ نسخة من BarcodeGenerator. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | ينشئ نسخة من BarcodeGenerator. |
## Methods

| Method | الوصف |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | يصدّر خصائص BarCode إلى xml-stream المحدد |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | يصدّر خصائص BarCode إلى xml-file المحدد |
| [generateBarCodeImage()](#generateBarCodeImage--) | إنشاء صورة الباركود وفق الإعدادات الحالية. |
| [getBarcodeType()](#getBarcodeType--) | نوع ترميز الباركود. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | النص المراد ترميزه. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | يستورد خصائص BarCode من xml-stream المحدد وينشئ مثيلاً من BarcodeGenerator. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | يستورد خصائص BarCode من xml-file المحدد وينشئ مثيلاً من BarcodeGenerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | حفظ BarCodeImage إلى تدفق بتنسيق محدد. |
| [save(String filename)](#save-java.lang.String-) | حفظ صورة الباركود إلى ملف محدد. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | حفظ صورة الباركود إلى ملف محدد بتنسيق محدد. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | نوع ترميز الباركود. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | تعيين codetext كسلسلة من البايتات. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | النص المراد ترميزه. |
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


ينشئ نسخة من BarcodeGenerator.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | نوع ترميز الباركود. استخدم الفئة EncodeTypes لإعداد ترميز. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


ينشئ نسخة من BarcodeGenerator.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | نوع ترميز الباركود. استخدم الفئة EncodeTypes لإعداد ترميز. |
| codeText | java.lang.String | النص المراد ترميزه. |

### dispose() {#dispose--}
```
public void dispose()
```


Clean up any resources being used.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


يصدّر خصائص BarCode إلى xml-stream المحدد

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xml | java.io.OutputStream | تدفق xml-stream |

**Returns:**
منطقي - ما إذا كان التصدير قد اكتمل بنجاح أم لا. يُعيد **True** في حالة النجاح؛ **False** خلاف ذلك
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


يصدّر خصائص BarCode إلى xml-file المحدد

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

**Returns:**
boolean - Whether or not export completed successfully.

Returns  **True**  in case of success;  **False**  Otherwise
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


إنشاء صورة الباركود وفق الإعدادات الحالية.

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          File outputFile = new File("test.png");
>          OutputStream os = new FileOutputStream(outputFile);
>          Bitmap generatedBitmap = generator.generateBarCodeImage();
>          generatedBitmap.compress(Bitmap.CompressFormat.PNG, 100, os);
>          os.flush();
>          os.close();
> ```

**Returns:**
android.graphics.Bitmap - Barcode image. See  Bitmap .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


نوع ترميز الباركود.

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


النص المراد ترميزه.

**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Generation parameters.

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


يستورد خصائص BarCode من xml-stream المحدد وينشئ مثيلاً من BarcodeGenerator.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xml | java.io.InputStream | تدفق xml-stream |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


يستورد خصائص BarCode من xml-file المحدد وينشئ مثيلاً من BarcodeGenerator.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| xmlFile | java.lang.String | The name of the file |

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


حفظ BarCodeImage إلى تدفق بتنسيق محدد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


حفظ صورة الباركود إلى ملف محدد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


حفظ صورة الباركود إلى ملف محدد بتنسيق محدد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| filename | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


نوع ترميز الباركود.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


تعيين codetext كسلسلة من البايتات.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| codeBytes | byte[] | بايتات codetext |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


النص المراد ترميزه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


يقوم بترميز **codeText** Unicode إلى تسلسل بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر استخدامًا. إذا كان الترميز يدعم ذلك، تقوم الدالة تلقائيًا بإدراج  [byte order mark (BOM)][byte order mark _BOM] .

هذه الدالة مخصصة للاستخدام مع الباركود ثنائي الأبعاد فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، إلخ). تتيح ترميز يدوي لنص Unicode باستخدام ترميزات وطنية أو خاصة؛ ومع ذلك، تُعتبر هذه الطريقة قديمة في التطبيقات الحديثة. لحالات الاستخدام الحديثة، يُنصح باستخدام ترميز  [ECI][]  لبيانات Unicode.

استخدام هذه الدالة مع باركود 1D، أو باركود متوافق مع GS1 (بما في ذلك 2D)، أو باركود HIBC (بما في ذلك 2D) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.

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
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```


[byte order mark _BOM]: https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding
[ECI]: https://en.wikipedia.org/wiki/Extended_Channel_Interpretation

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| codeText | java.lang.String | سلسلة CodeText |
| الترميز | java.nio.charset.Charset | الترميز المطبق |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


يقوم بترميز **codeText** Unicode إلى تسلسل بايتات باستخدام **encoding** المحدد. UTF-8 هو الترميز الأكثر استخدامًا. إذا كان الترميز يدعم ذلك وتم تعيين **insertBOM** إلى  true ، فإن الدالة تتضمن  [byte order mark (BOM)][byte order mark _BOM] .

هذه الدالة مخصصة للاستخدام مع الباركود ثنائي الأبعاد فقط (مثل Aztec، QR، DataMatrix، PDF417، MaxiCode، DotCode، HanXin، RectMicroQR، إلخ). تتيح ترميز يدوي لنص Unicode باستخدام ترميزات وطنية أو خاصة؛ ومع ذلك، تُعتبر هذه الطريقة قديمة في التطبيقات الحديثة. لحالات الاستخدام الحديثة، يُنصح باستخدام ترميز  [ECI][]  لبيانات Unicode.

استخدام هذه الدالة مع باركود 1D، أو باركود متوافق مع GS1 (بما في ذلك 2D)، أو باركود HIBC (بما في ذلك 2D) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| codeText | java.lang.String | سلسلة CodeText |
| الترميز | java.nio.charset.Charset | الترميز المطبق |
| insertBOM | boolean | يشير إلى ما إذا كان يجب إدراج علامة ترتيب البايتات (BOM) عندما يدعم الترميز المحدد ذلك (مثل UTF-8، UTF-16، UTF-32). إذا تم تعيينه إلى  true ، تُضاف الـ BOM؛ إذا كان  false ، تُحذف الـ BOM حتى لو كان الترميز يستخدمها عادةً. |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

