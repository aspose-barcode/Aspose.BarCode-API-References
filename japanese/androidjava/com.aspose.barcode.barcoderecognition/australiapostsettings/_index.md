---
title: "AustraliaPostSettings"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "AustraliaPostのデコードパラメータです。"
type: docs
weight: 10
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/australiapostsettings/
---
**Inheritance:**
java.lang.Object
```
public class AustraliaPostSettings
```

AustraliaPost のデコードパラメータ。AustraliaPost シンボロジーの認識データに影響を与えるパラメータを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomerInformationDecoder()](#getCustomerInformationDecoder--) | AustraliaPost のシンボルで使用される Customer Information Field デコード用の公開インターフェイスです。 |
| [getCustomerInformationInterpretingType()](#getCustomerInformationInterpretingType--) | AustralianPost バーコードの顧客情報の解釈タイプを取得または設定します。デフォルトは CustomerInformationInterpretingType.OTHER です。 |
| [getIgnoreEndingFillingPatternsForCTable()](#getIgnoreEndingFillingPatternsForCTable--) | CTable メソッドでデコード中に顧客情報フィールドの最後のフィリングパターンを無視させる AustraliaPost デコーダのフラグです。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)](#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-) | AustraliaPost のシンボルで使用される Customer Information Field デコード用の公開インターフェイスです。 |
| [setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)](#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-) | AustralianPost バーコードの顧客情報の解釈タイプを取得または設定します。デフォルトは CustomerInformationInterpretingType.OTHER です。 |
| [setIgnoreEndingFillingPatternsForCTable(boolean value)](#setIgnoreEndingFillingPatternsForCTable-boolean-) | CTable メソッドでデコード中に顧客情報フィールドの最後のフィリングパターンを無視させる AustraliaPost デコーダのフラグです。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomerInformationDecoder() {#getCustomerInformationDecoder--}
```
public AustraliaPostCustomerInformationDecoder getCustomerInformationDecoder()
```


AustraliaPost のシンボルで使用される Customer Information Field デコード用の公開インターフェイスです。

**Returns:**
[AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) - Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
### getCustomerInformationInterpretingType() {#getCustomerInformationInterpretingType--}
```
public CustomerInformationInterpretingType getCustomerInformationInterpretingType()
```


AustralianPost バーコードの顧客情報の解釈タイプを取得または設定します。デフォルトは CustomerInformationInterpretingType.OTHER です。

**Returns:**
[CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) - The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode
### getIgnoreEndingFillingPatternsForCTable() {#getIgnoreEndingFillingPatternsForCTable--}
```
public boolean getIgnoreEndingFillingPatternsForCTable()
```


CTable メソッドでデコード中に顧客情報フィールドの最後のフィリングパターンを無視させるフラグです。CTable エンコーディングメソッドはエンコーディングテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。例 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Returns:**
boolean - CTable メソッドでのデコード中に最後のフィリングパターンを無視させる AustraliaPost デコーダのフラグです
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




### setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value) {#setCustomerInformationDecoder-com.aspose.barcode.barcoderecognition.AustraliaPostCustomerInformationDecoder-}
```
public void setCustomerInformationDecoder(AustraliaPostCustomerInformationDecoder value)
```


AustraliaPost のシンボルで使用される Customer Information Field デコード用の公開インターフェイスです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [AustraliaPostCustomerInformationDecoder](../../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) |  |

### setCustomerInformationInterpretingType(CustomerInformationInterpretingType value) {#setCustomerInformationInterpretingType-com.aspose.barcode.barcoderecognition.CustomerInformationInterpretingType-}
```
public void setCustomerInformationInterpretingType(CustomerInformationInterpretingType value)
```


AustralianPost バーコードの顧客情報の解釈タイプを取得または設定します。デフォルトは CustomerInformationInterpretingType.OTHER です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [CustomerInformationInterpretingType](../../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost バーコードの顧客情報の解釈タイプ（CTable、NTable、または Other） |

### setIgnoreEndingFillingPatternsForCTable(boolean value) {#setIgnoreEndingFillingPatternsForCTable-boolean-}
```
public void setIgnoreEndingFillingPatternsForCTable(boolean value)
```


CTable メソッドでデコード中に顧客情報フィールドの最後のフィリングパターンを無視させるフラグです。CTable エンコーディングメソッドはエンコーディングテーブルにギャップがなく、フィリングパターンのシーケンス "333" は文字 "z" としてデコードされます。例 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA\_POST, "5912345678AB"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C\_TABLE); Bitmap image = generator.generateBarCodeImage(); BarCodeReader reader = new BarCodeReader(image, DecodeType.AUSTRALIA\_POST); reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C\_TABLE); reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true); for(BarCodeResult result : reader.readBarCodes()) \{ System.out.println("BarCode Type: " + result.getCodeType()); System.out.println("BarCode CodeText: " + result.getCodeText()); \}

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

