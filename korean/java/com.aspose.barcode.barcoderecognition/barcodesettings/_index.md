---
title: "BarcodeSettings"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "주요 BarCode 디코딩 매개변수."
type: docs
weight: 19
url: /ko/java/com.aspose.barcode.barcoderecognition/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

주요 BarCode 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustraliaPost()](#getAustraliaPost--) | AustraliaPost 디코딩 매개변수를 가져옵니다 |
| [getChecksumValidation()](#getChecksumValidation--) | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. |
| [getClass()](#getClass--) |  |
| [getDetectEncoding()](#getDetectEncoding--) | Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그. |
| [getStripFNC()](#getStripFNC--) | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. |
| [hashCode()](#hashCode--) |  |
| [isOnlyRequestedTypes()](#isOnlyRequestedTypes--) | 인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumValidation(ChecksumValidation value)](#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-) | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. |
| [setDetectEncoding(boolean value)](#setDetectEncoding-boolean-) | Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그. |
| [setOnlyRequestedTypes(boolean value)](#setOnlyRequestedTypes-boolean-) | 인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. |
| [setStripFNC(boolean value)](#setStripFNC-boolean-) | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustraliaPost() {#getAustraliaPost--}
```
public AustraliaPostSettings getAustraliaPost()
```


AustraliaPost 디코딩 매개변수를 가져옵니다

**Returns:**
[AustraliaPostSettings](../../com.aspose.barcode.barcoderecognition/australiapostsettings) - The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology
### getChecksumValidation() {#getChecksumValidation--}
```
public ChecksumValidation getChecksumValidation()
```


인식 중에 1D 및 우편 바코드에 대한 체크섬 검증을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다. 체크섬이 사용되지 않는 경우: Codabar, PatchCode, Pharmacode, DataLogic2of5 체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN 체크섬이 항상 사용되는 경우: 나머지 심볼 예제 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Returns:**
[ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) - Enable checksum validation during recognition for 1D and Postal barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDetectEncoding() {#getDetectEncoding--}
```
public boolean getDetectEncoding()
```


Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그. 기본값은 true입니다.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

값: Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그

**Returns:**
boolean
### getStripFNC() {#getStripFNC--}
```
public boolean getStripFNC()
```


코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다. 예제 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOnlyRequestedTypes() {#isOnlyRequestedTypes--}
```
public boolean isOnlyRequestedTypes()
```


인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형으로 인식된 바코드는 필터링됩니다. 기본값은 false입니다.

예제:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Returns:**
boolean - 명시적으로 요청된 바코드 유형만 반환되는 경우 true; 그렇지 않으면 false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumValidation(ChecksumValidation value) {#setChecksumValidation-com.aspose.barcode.barcoderecognition.ChecksumValidation-}
```
public void setChecksumValidation(ChecksumValidation value)
```


인식 중에 1D 및 우편 바코드에 대한 체크섬 검증을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다. 체크섬이 사용되지 않는 경우: Codabar, PatchCode, Pharmacode, DataLogic2of5 체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN 체크섬이 항상 사용되는 경우: 나머지 심볼 예제 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN\_13, "1234567890128"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.EAN\_13); //checksum disabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \} BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.EAN\_13); //checksum enabled reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON); for (BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode CodeText: " + result.CodeText); System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue()); System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()); \}

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ChecksumValidation](../../com.aspose.barcode.barcoderecognition/checksumvalidation) | 1D 및 우편 바코드 인식 중에 체크섬 검증을 활성화합니다. |

### setDetectEncoding(boolean value) {#setDetectEncoding-boolean-}
```
public void setDetectEncoding(boolean value)
```


Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그. 기본값은 true입니다.

--------------------

> ```
> This sample shows how to detect text encoding on the fly if DetectEncoding is enabled
>  
> 
>  ByteArrayOutputStream ms = new ByteArrayOutputStream();
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>  generator.setCodeText("\u0421\u043b\u043e\u0432\u043e", StandardCharsets.UTF_8);
>  generator.save(ms, BarCodeImageFormat.PNG);
> 
>  BarCodeReader reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(true);
>  for (BarCodeResult result : reader.readBarCodes())
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  //detect encoding is disabled
>  reader = new BarCodeReader(new ByteArrayInputStream(ms.toByteArray()), DecodeType.QR);
>  reader.getBarcodeSettings().setDetectEncoding(false);
>  for (BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText());
> ```

값: Unicode 코드셋에 대한 코드텍스트 인코딩을 엔진이 감지하도록 강제하는 플래그

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setOnlyRequestedTypes(boolean value) {#setOnlyRequestedTypes-boolean-}
```
public void setOnlyRequestedTypes(boolean value)
```


인식하도록 명시적으로 지정된 바코드 유형만 반환합니다. 활성화하면 다른 호환 또는 동등한 유형으로 인식된 바코드는 필터링됩니다. 기본값은 false입니다.

예제:

```
// generate EAN13 barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894");
 generator.save("c:\\test.png");

 // recognize only UPCA barcodes (no results, because source is EAN13)
 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader.getBarcodeSettings().setOnlyRequestedTypes(true);
 for (BarCodeResult result : reader.readBarCodes())
 {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }

 // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN
 // (EAN13 will be returned as UPCA-equivalent)
 BarCodeReader reader2 = new BarCodeReader("c:\\test.png", DecodeType.UPCA);
 reader2.getBarcodeSettings().setOnlyRequestedTypes(false);
 for (BarCodeResult result : reader2.readBarCodes()) {
     System.out.println("BarCode CodeText: " + result.getCodeText());
 }
```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setStripFNC(boolean value) {#setStripFNC-boolean-}
```
public void setStripFNC(boolean value)
```


코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false입니다. 예제 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_CODE\_128, "(02)04006664241007(37)1(400)7019590754"); generator.save("c:/test.png"); BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC disabled reader.getBarcodeSettings().setStripFNC(false); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \} BarCodeReader reader = new BarCodeReader("c:/test.png", DecodeType.CODE\_128); //StripFNC enabled reader.getBarcodeSettings().setStripFNC(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.our.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean | 코드텍스트에서 FNC1, FNC2, FNC3 문자를 제거합니다. 기본값은 false. |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

