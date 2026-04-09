---
title: BarcodeGenerator
second_title: Aspose.BarCode for Android via Java API Reference
description: 백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.
type: docs
weight: 13
url: /ko/androidjava/com.aspose.barcode.generation/barcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class BarcodeGenerator
```

백엔드 바코드 이미지 생성을 위한 BarcodeGenerator.

지원되는 심볼: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

--------------------

> ```
> This sample shows how to create and save a barcode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.setCodeText("123ABC");
>          generator.save("code128.png");
> ```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [BarcodeGenerator(BaseEncodeType type)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-) | BarcodeGenerator의 인스턴스를 생성합니다. |
| [BarcodeGenerator(BaseEncodeType type, String codeText)](#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-) | BarcodeGenerator의 인스턴스를 생성합니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [dispose()](#dispose--) | Clean up any resources being used. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportToXml(OutputStream xml)](#exportToXml-java.io.OutputStream-) | 지정된 XML 스트림으로 BarCode 속성을 내보냅니다. |
| [exportToXml(String xmlFile)](#exportToXml-java.lang.String-) | 지정된 XML 파일로 BarCode 속성을 내보냅니다. |
| [generateBarCodeImage()](#generateBarCodeImage--) | 현재 설정으로 바코드 이미지를 생성합니다. |
| [getBarcodeType()](#getBarcodeType--) | 바코드 심볼 유형. |
| [getClass()](#getClass--) |  |
| [getCodeText()](#getCodeText--) | 인코딩할 텍스트. |
| [getParameters()](#getParameters--) | Generation parameters. |
| [hashCode()](#hashCode--) |  |
| [importFromXml(InputStream xml)](#importFromXml-java.io.InputStream-) | 지정된 xml 스트림에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| [importFromXml(String xmlFile)](#importFromXml-java.lang.String-) | 지정된 xml 파일에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | BarCodeImage를 지정된 형식으로 스트림에 저장합니다. |
| [save(String filename)](#save-java.lang.String-) | 바코드 이미지를 지정된 파일에 저장합니다. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | 바코드 이미지를 지정된 형식으로 지정된 파일에 저장합니다. |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | 바코드 심볼 유형. |
| [setCodeText(byte[] codeBytes)](#setCodeText-byte---) | 코드텍스트를 바이트 시퀀스로 설정합니다. |
| [setCodeText(String value)](#setCodeText-java.lang.String-) | 인코딩할 텍스트. |
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


BarcodeGenerator의 인스턴스를 생성합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 바코드 심볼 유형. EncodeTypes 클래스를 사용하여 심볼을 설정합니다. |

### BarcodeGenerator(BaseEncodeType type, String codeText) {#BarcodeGenerator-com.aspose.barcode.generation.BaseEncodeType-java.lang.String-}
```
public BarcodeGenerator(BaseEncodeType type, String codeText)
```


BarcodeGenerator의 인스턴스를 생성합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| type | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | 바코드 심볼 유형. EncodeTypes 클래스를 사용하여 심볼을 설정합니다. |
| codeText | java.lang.String | 인코딩할 텍스트. |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exportToXml(OutputStream xml) {#exportToXml-java.io.OutputStream-}
```
public boolean exportToXml(OutputStream xml)
```


지정된 XML 스트림으로 BarCode 속성을 내보냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| xml | java.io.OutputStream | xml 스트림 |

**Returns:**
boolean - 내보내기가 성공적으로 완료되었는지 여부. 성공 시 **True**, 그렇지 않으면 **False** 반환
### exportToXml(String xmlFile) {#exportToXml-java.lang.String-}
```
public boolean exportToXml(String xmlFile)
```


지정된 XML 파일로 BarCode 속성을 내보냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| xmlFile | java.lang.String | 파일의 이름 |

**Returns:**
boolean - 내보내기가 성공적으로 완료되었는지 여부.

성공인 경우 **True** 를 반환하고, 그렇지 않으면 **False** 를 반환합니다.
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


현재 설정으로 바코드 이미지를 생성합니다.

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


바코드 심볼 유형.

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


인코딩할 텍스트.

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


지정된 xml 스트림에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| xml | java.io.InputStream | xml 스트림 |

**Returns:**
[BarcodeGenerator](../../com.aspose.barcode.generation/barcodegenerator) - BarcodeGenerator instance
### importFromXml(String xmlFile) {#importFromXml-java.lang.String-}
```
public static BarcodeGenerator importFromXml(String xmlFile)
```


지정된 xml 파일에서 BarCode 속성을 가져와 BarcodeGenerator 인스턴스를 생성합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| xmlFile | java.lang.String | 파일의 이름 |

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


BarCodeImage를 지정된 형식으로 스트림에 저장합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) |  |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


바코드 이미지를 지정된 파일에 저장합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | Path to save to. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


바코드 이미지를 지정된 형식으로 지정된 파일에 저장합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | Path to save to. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifies the file format of the output image. |

### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


바코드 심볼 유형.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setCodeText(byte[] codeBytes) {#setCodeText-byte---}
```
public void setCodeText(byte[] codeBytes)
```


코드텍스트를 바이트 시퀀스로 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| codeBytes | byte[] | 코드 텍스트의 바이트 |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```


인코딩할 텍스트.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCodeText(String codeText, Charset encoding) {#setCodeText-java.lang.String-java.nio.charset.Charset-}
```
public void setCodeText(String codeText, Charset encoding)
```


지정된 **encoding**을 사용하여 유니코드 **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8이 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 지원하는 경우, 함수는 자동으로 [byte order mark (BOM)][byte order mark _BOM]을 삽입합니다.

이 함수는 2D 바코드 전용(예: Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR 등)으로 사용하도록 설계되었습니다. 국가별 또는 특수 인코딩을 사용하여 유니코드 텍스트를 수동으로 인코딩할 수 있지만, 이 방법은 최신 애플리케이션에서는 구식으로 간주됩니다. 최신 사용 사례에서는 유니코드 데이터에 대해 [ECI][] 인코딩을 권장합니다.

1D 바코드, GS1 규격 바코드(2D 포함) 또는 HIBC 바코드(2D 포함)와 함께 이 함수를 사용하는 것은 해당 바코드 표준에서 지원되지 않으며 예측할 수 없는 결과를 초래할 수 있습니다.

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 문자열 |
| 인코딩 | java.nio.charset.Charset | 적용된 인코딩 |

### setCodeText(String codeText, Charset encoding, boolean insertBOM) {#setCodeText-java.lang.String-java.nio.charset.Charset-boolean-}
```
public void setCodeText(String codeText, Charset encoding, boolean insertBOM)
```


지정된 **encoding**을 사용하여 유니코드 **codeText**를 바이트 시퀀스로 인코딩합니다. UTF-8이 가장 일반적으로 사용되는 인코딩입니다. 인코딩이 지원하고 **insertBOM**가 true로 설정된 경우, 함수는 [byte order mark (BOM)][byte order mark _BOM]을 포함합니다.

이 함수는 2D 바코드 전용(예: Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR 등)으로 사용하도록 설계되었습니다. 국가별 또는 특수 인코딩을 사용하여 유니코드 텍스트를 수동으로 인코딩할 수 있지만, 이 방법은 최신 애플리케이션에서는 구식으로 간주됩니다. 최신 사용 사례에서는 유니코드 데이터에 대해 [ECI][] 인코딩을 권장합니다.

1D 바코드, GS1 규격 바코드(2D 포함) 또는 HIBC 바코드(2D 포함)와 함께 이 함수를 사용하는 것은 해당 바코드 표준에서 지원되지 않으며 예측할 수 없는 결과를 초래할 수 있습니다.

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| codeText | java.lang.String | CodeText 문자열 |
| 인코딩 | java.nio.charset.Charset | 적용된 인코딩 |
| insertBOM | boolean | 지정된 인코딩이 지원하는 경우 바이트 순서 표시(BOM)를 삽입할지 여부를 나타냅니다(예: UTF-8, UTF-16, UTF-32). true로 설정하면 BOM이 추가되고, false로 설정하면 인코딩이 일반적으로 BOM을 사용하더라도 생략됩니다. |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

