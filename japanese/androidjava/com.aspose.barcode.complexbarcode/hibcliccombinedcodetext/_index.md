---
title: HIBCLICCombinedCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: 一次および二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。
type: docs
weight: 14
url: /ja/androidjava/com.aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICCombinedCodetext extends HIBCLICComplexCodetext
```

一次および二次データを格納する HIBC LIC コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

--------------------

> ```
> This sample shows how to encode and decode HIBC LIC using HIBCLICCombinedCodetext.
>  
> 
>  HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
>  combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
>  combinedCodetext.setPrimaryData(new PrimaryData());
>  combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
>  combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
>  combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
>  combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
>  combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
>  combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
>  combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
>  combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
>  combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
>  ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
>  BufferedImage image = generator.generateBarCodeImage();
>  BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC);
>  reader.readBarCodes();
>  String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.tryDecodeHIBCLIC(codetext);
>  System.out.println("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
>  System.out.println("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
>  System.out.println("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
>  System.out.println("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
>  System.out.println("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
>  System.out.println("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
>  System.out.println("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
>  System.out.println("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [HIBCLICCombinedCodetext()](#HIBCLICCombinedCodetext--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  HIBCLICCombinedCodetext  値と等しいかどうかを示す値を返します。 |
| [getBarcodeType()](#getBarcodeType--) | バーコードのタイプを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | コードテキストを構築します。 |
| [getPrimaryData()](#getPrimaryData--) | 一次データを識別します。 |
| [getSecondaryAndAdditionalData()](#getSecondaryAndAdditionalData--) | 二次データおよび追加の補足データを識別します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストからインスタンスを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | バーコードのタイプを取得または設定します。 |
| [setPrimaryData(PrimaryData value)](#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-) | 一次データを識別します。 |
| [setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)](#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | 二次データおよび追加の補足データを識別します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICCombinedCodetext() {#HIBCLICCombinedCodetext--}
```
public HIBCLICCombinedCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  HIBCLICCombinedCodetext  値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための  HIBCLICCombinedCodetext  値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードタイプを取得または設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC エンコードタイプを使用してエンコードできます。デフォルト値: HIBCCode39LIC。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


コードテキストを構築します。

**Returns:**
java.lang.String - 構築されたコードテキスト
### getPrimaryData() {#getPrimaryData--}
```
public PrimaryData getPrimaryData()
```


一次データを識別します。

**Returns:**
[PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata)
### getSecondaryAndAdditionalData() {#getSecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData getSecondaryAndAdditionalData()
```


二次データおよび追加の補足データを識別します。

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


構築されたコードテキストからインスタンスを初期化します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 構築されたコードテキスト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


バーコードタイプを取得または設定します。HIBC LIC コードテキストは HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC、HIBCQRLIC エンコードタイプを使用してエンコードできます。デフォルト値: HIBCCode39LIC。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setPrimaryData(PrimaryData value) {#setPrimaryData-com.aspose.barcode.complexbarcode.PrimaryData-}
```
public void setPrimaryData(PrimaryData value)
```


一次データを識別します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PrimaryData](../../com.aspose.barcode.complexbarcode/primarydata) |  |

### setSecondaryAndAdditionalData(SecondaryAndAdditionalData value) {#setSecondaryAndAdditionalData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setSecondaryAndAdditionalData(SecondaryAndAdditionalData value)
```


二次データおよび追加の補足データを識別します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

