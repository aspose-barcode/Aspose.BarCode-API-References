---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: DotCode 인식 바코드의 특수 데이터를 저장합니다
type: docs
weight: 33
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

DotCode 인식 바코드의 특수 데이터를 저장합니다

이 샘플은 DotCode 원시 값을 가져오는 방법을 보여줍니다.

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | 코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | DotCode 구조화 추가 모드 바코드의 개수를 가져옵니다. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode 구조화 추가 모드 바코드의 개수를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [isReaderInitialization()](#isReaderInitialization--) | 코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | 첫 번째 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | 첫 번째 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |
| [toString()](#toString--) | 이 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 개수보다 작거나 같아야 합니다. 기본값은 -1입니다.

값: DotCode 구조화 추가 모드 바코드의 ID입니다.

**Returns:**
int - DotCode 구조화 추가 모드 바코드의 ID입니다.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


DotCode 구조화 추가 모드 바코드의 개수를 가져옵니다. 기본값은 -1이며, 개수는 1에서 35 사이여야 합니다.

값: DotCode 구조화 추가 모드 바코드의 개수입니다.

**Returns:**
int - DotCode 구조화 추가 모드 바코드의 개수입니다.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode 구조화 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 개수보다 작거나 같아야 합니다. 기본값은 -1입니다.

값: DotCode 구조화 추가 모드 바코드의 ID입니다.

**Returns:**
int - DotCode 구조화 추가 모드 바코드의 ID입니다.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode 구조화 추가 모드 바코드의 개수를 가져옵니다. 기본값은 -1이며, 개수는 1에서 35 사이여야 합니다.

값: DotCode 구조화 추가 모드 바코드의 개수입니다.

**Returns:**
int - DotCode 구조화 추가 모드 바코드의 개수입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


모든 매개변수가 기본값만 가지고 있는지 테스트합니다.

값: 모든 매개변수가 기본값만 가지고 있으면 **true**, 그렇지 않으면 **false**를 반환합니다.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


첫 번째 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 첫 번째 비교 값 |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 두 번째 비교 값 |

**Returns:**
boolean -  **true**  첫 번째가 두 번째와 동일한 값을 가지고 있는 경우; 그렇지 않으면 **false**.
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


첫 번째 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 첫 번째 비교 값 |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 두 번째 비교 값 |

**Returns:**
boolean -  **true**  첫 번째가 두 번째와 다른 값을 가지고 있는 경우; 그렇지 않으면 **false**.
### toString() {#toString--}
```
public String toString()
```


이 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters)를 나타내는 문자열입니다.
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

