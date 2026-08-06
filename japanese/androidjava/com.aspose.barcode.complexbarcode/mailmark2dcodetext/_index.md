---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。
type: docs
weight: 23
url: /ja/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。
## Constructors

| Constructor | Description |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | バーコードのタイプを取得します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | 要求されているReturn to Senderサービスのレベルを示すフラグです。 |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Return to Senderポストコードを含みますが、DPSは含みません。 |
| [getSupplyChainID()](#getSupplyChainID--) | メールに関与する顧客のユニークなグループを識別します。 |
| [getUPUCountryID()](#getUPUCountryID--) | UPU国IDを識別します。最大長さ: 4文字。 |
| [getVersionID()](#getVersionID--) | 各Information Type IDに関連するバーコードバージョンを識別します。 |
| [getclass()](#getclass--) | アイテムのクラスを識別します。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 要求されているReturn to Senderサービスのレベルを示すフラグです。 |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Return to Senderポストコードを含みますが、DPSは含みません。 |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | メールに関与する顧客のユニークなグループを識別します。 |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU国IDを識別します。最大長さ: 4文字。 |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | 各Information Type IDに関連するバーコードバージョンを識別します。 |
| [setclass(String value)](#setclass-java.lang.String-) | アイテムのクラスを識別します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードのタイプを取得します。

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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - 構築されたコードテキスト
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


顧客が使用できる任意のスペースです。タイプ別の最大長さ: Type 7: 6文字、Type 9: 45文字、Type 29: 25文字

**Returns:**
java.lang.String - 顧客コンテンツ
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrixバーコードのエンコードモードです。デフォルト値: DataMatrixEncodeMode.C40。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


DPS付きの配達先住所の郵便番号を含みます。内陸の場合、郵便番号/DPSは以下の文字数で構成されます。エリア (1または2文字) 区 (1または2文字) セクター (1文字) ユニット (2文字) DPS (2文字)。郵便番号とDPSは有効なPAF®形式に準拠している必要があります。

**Returns:**
java.lang.String - DPS付き配達先住所の郵便番号
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


各製品タイプに対するRoyal Mail Mailmarkバーコードペイロードを識別します。有効な値: '0' - 国内ソート・アンソート、'A' - オンライン郵便、'B' - フランキング、'C' - コンソリデーション

**Returns:**
java.lang.String - 情報タイプID
### getItemID() {#getItemID--}
```
public int getItemID()
```


Supply Chain ID内のユニークなアイテムを識別します。すべてのMailmarkバーコードはIDを保持する必要があり、少なくとも90日間ユニークに識別できます。最大値: 99999999。

**Returns:**
int - Supply Chain ID内のアイテム
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


要求されているReturn to Senderサービスのレベルを示すフラグです。

**Returns:**
java.lang.String - RTSフラグ
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Return to Senderポストコードを含みますが、DPSは含みません。PC（DPSなし）はPAF®形式に準拠している必要があります。

**Returns:**
java.lang.String - Return to Senderポストコード（DPSなし）
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。

**Returns:**
int - Supply chain ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


UPU国IDを識別します。最大長さ: 4文字。

**Returns:**
java.lang.String - Country ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


各Information Type IDに関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2'〜'9'、および 'A'〜'Z' は将来の使用のために予備として予約されています。

**Returns:**
java.lang.String - Version ID
### getclass() {#getclass--}
```
public String getclass()
```


アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - エコノミー（小売） '5' - Deffered（小売） '8' - プレミアム（ネットワークアクセス） '9' - スタンダード（ネットワークアクセス）

**Returns:**
java.lang.String - アイテムのクラス
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Initializes Mailmark data from constructed codetext.

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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


顧客が使用できる任意のスペースです。タイプ別の最大長さ: Type 7: 6文字、Type 9: 45文字、Type 29: 25文字

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


DPS付きの配達先住所の郵便番号を含みます。内陸の場合、郵便番号/DPSは以下の文字数で構成されます。エリア (1または2文字) 区 (1または2文字) セクター (1文字) ユニット (2文字) DPS (2文字)。郵便番号とDPSは有効なPAF®形式に準拠している必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


各製品タイプに対するRoyal Mail Mailmarkバーコードペイロードを識別します。有効な値: '0' - 国内ソート・アンソート、'A' - オンライン郵便、'B' - フランキング、'C' - コンソリデーション

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Supply Chain ID内のユニークなアイテムを識別します。すべてのMailmarkバーコードはIDを保持する必要があり、少なくとも90日間ユニークに識別できます。最大値: 99999999。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


要求されているReturn to Senderサービスのレベルを示すフラグです。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Return to Senderポストコードを含みますが、DPSは含みません。PC（DPSなし）はPAF®形式に準拠している必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


UPU国IDを識別します。最大長さ: 4文字。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


各Information Type IDに関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2'〜'9'、および 'A'〜'Z' は将来の使用のために予備として予約されています。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - エコノミー（小売） '5' - Deffered（小売） '8' - プレミアム（ネットワークアクセス） '9' - スタンダード（ネットワークアクセス）

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String | class of the item |

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

