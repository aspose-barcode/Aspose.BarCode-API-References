---
title: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "ComplexBarcodeGenerator for 백엔드 복합 바코드 예:"
type: docs
weight: 12
url: /ko/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

백엔드 복합 바코드 (e.g. SwissQR) 이미지 생성을 위한 ComplexBarcodeGenerator.

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | ComplexBarcodeGenerator의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [dispose()](#dispose--) | 사용 중인 모든 리소스를 정리합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | 현재 설정에 따라 복합 바코드 이미지를 생성합니다. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | 생성 매개변수. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | 현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다. |
| [save(String filename)](#save-java.lang.String-) | 현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | 현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


ComplexBarcodeGenerator의 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | 복합 코드 텍스트 |

### dispose() {#dispose--}
```
public void dispose()
```


사용 중인 모든 리소스를 정리합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


현재 설정에 따라 복합 바코드 이미지를 생성합니다.

**Returns:**
android.graphics.Bitmap - 바코드 이미지. Bitmap을 참조하십시오.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


생성 매개변수.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
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




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 출력 System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 출력 이미지의 파일 형식을 지정합니다. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 저장 경로. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


현재 설정에 따라 복합 바코드 이미지를 생성하고 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | java.lang.String | 저장 경로. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | 출력 이미지의 파일 형식을 지정합니다. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

