---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "Royal Mail 2D Mailmarkコードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
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

Royal Mail 2D Mailmarkコードに埋め込まれたテキストをエンコードおよびデコードするクラス。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Mailmark2DCodetext クラスのデフォルトインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | バーコードの種類を取得します。 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark データからコードテキストを構築します。 |
| [getCustomerContent()](#getCustomerContent--) | 顧客が使用できるオプションのスペースです。 |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Data Matrix バーコードのエンコードモードです。 |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | DPS を含む配達先住所の郵便番号が含まれます。内陸の場合、郵便番号/DP は以下の文字数を含みます。 |
| [getInformationTypeID()](#getInformationTypeID--) | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。 |
| [getItemID()](#getItemID--) | サプライチェーン ID 内のユニークな項目を識別します。 |
| [getRTSFlag()](#getRTSFlag--) | 返送サービスの要求レベルを示すフラグです。 |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | 返送先の郵便コードが含まれますが、DPS は含まれません。 |
| [getSupplyChainID()](#getSupplyChainID--) | 郵送に関与するユニークな顧客グループを識別します。 |
| [getUPUCountryID()](#getUPUCountryID--) | UPU 国 ID を識別します。最大長さ: 4 文字。 |
| [getVersionID()](#getVersionID--) | 各情報タイプ ID に関連するバーコードバージョンを識別します。 |
| [getclass()](#getclass--) | アイテムのクラスを識別します。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストから Mailmark データを初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | 顧客が使用できるオプションのスペースです。 |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Data Matrix バーコードのエンコードモードです。 |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | DPS を含む配達先住所の郵便番号が含まれます。内陸の場合、郵便番号/DP は以下の文字数を含みます。 |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。 |
| [setItemID(int value)](#setItemID-int-) | サプライチェーン ID 内のユニークな項目を識別します。 |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 返送サービスの要求レベルを示すフラグです。 |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | 返送先の郵便コードが含まれますが、DPS は含まれません。 |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | 郵送に関与するユニークな顧客グループを識別します。 |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU 国 ID を識別します。最大長さ: 4 文字。 |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | 各情報タイプ ID に関連するバーコードバージョンを識別します。 |
| [setclass(String value)](#setclass-java.lang.String-) | アイテムのクラスを識別します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Mailmark2DCodetext クラスのデフォルトインスタンスを作成します。

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードの種類を取得します。

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


Mailmark データからコードテキストを構築します。

**Returns:**
java.lang.String - 構築されたコードテキスト
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


顧客が使用するための任意のスペース。タイプ別の最大長さ: タイプ7: 6文字、タイプ9: 45文字、タイプ29: 25文字

**Returns:**
java.lang.String - 顧客コンテンツ
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrixバーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.C40。

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


DPS付きの配送先住所の郵便番号を含みます。内陸の場合、郵便番号/DPは次の文字数を含みます。エリア（1または2文字）地区（1または2文字）セクター（1文字）ユニット（2文字）DPS（2文字）。郵便番号とDPSは有効なPAF®形式に準拠している必要があります。

**Returns:**
java.lang.String - DPS付きの配送先住所の郵便番号
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


各製品タイプのRoyal Mail Mailmarkバーコードペイロードを識別します。有効な値: '0' - 国内の仕分け済みおよび未仕分け、'A' - オンライン郵便、'B' - フランキング、'C' - コンソリデーション

**Returns:**
java.lang.String - 情報タイプID
### getItemID() {#getItemID--}
```
public int getItemID()
```


サプライチェーンID内のユニークなアイテムを識別します。すべてのMailmarkバーコードはIDを保持する必要があり、少なくとも90日間ユニークに識別できます。最大値: 99999999。

**Returns:**
int - サプライチェーンID内のアイテム
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


返送サービスの要求レベルを示すフラグです。

**Returns:**
java.lang.String - RTSフラグ
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Return to Sender（RTO）ポストコードを含みますが、DPSは含みません。DPSなしのPCはPAF®形式に準拠している必要があります。

**Returns:**
java.lang.String - DPSなしのReturn to Senderポストコード
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


郵便物に関与する顧客のユニークなグループを識別します。最大値: 9999999。

**Returns:**
int - サプライチェーンID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


UPU 国 ID を識別します。最大長さ: 4 文字。

**Returns:**
java.lang.String - 国ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


各情報タイプIDに関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2'〜'9'、および 'A'〜'Z' は将来の使用のために予備として予約されています。

**Returns:**
java.lang.String - バージョンID
### getclass() {#getclass--}
```
public String getclass()
```


アイテムのクラスを識別します。有効な値: '1' - 1C（小売）'2' - 2C（小売）'3' - エコノミー（小売）'5' - Deffered（小売）'8' - Premium（Network Access）'9' - Standard（Network Access）

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


構築されたコードテキストから Mailmark データを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
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


顧客が使用するための任意のスペース。タイプ別の最大長さ: タイプ7: 6文字、タイプ9: 45文字、タイプ29: 25文字

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 顧客コンテンツ |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Datamatrixバーコードのエンコードモード。デフォルト値: EncodeMode.C40。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Data Matrix バーコードのエンコードモードです。 |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Data Matrixバーコードのサイズ |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


DPS付きの配送先住所の郵便番号を含みます。内陸の場合、郵便番号/DPは次の文字数を含みます。エリア（1または2文字）地区（1または2文字）セクター（1文字）ユニット（2文字）DPS（2文字）。郵便番号とDPSは有効なPAF®形式に準拠している必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | DPS付きの配送先住所の郵便番号 |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


各製品タイプのRoyal Mail Mailmarkバーコードペイロードを識別します。有効な値: '0' - 国内の仕分け済みおよび未仕分け、'A' - オンライン郵便、'B' - フランキング、'C' - コンソリデーション

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 情報タイプID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


サプライチェーンID内のユニークなアイテムを識別します。すべてのMailmarkバーコードはIDを保持する必要があり、少なくとも90日間ユニークに識別できます。最大値: 99999999。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | Supply Chain ID 内の項目 |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


返送サービスの要求レベルを示すフラグです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Return to Sender（RTO）ポストコードを含みますが、DPSは含みません。DPSなしのPCはPAF®形式に準拠している必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 差出人返送郵便コード（ただし DPS なし） |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


郵便物に関与する顧客のユニークなグループを識別します。最大値: 9999999。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int | サプライチェーンID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


UPU 国 ID を識別します。最大長さ: 4 文字。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 国 ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


各情報タイプIDに関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2'〜'9'、および 'A'〜'Z' は将来の使用のために予備として予約されています。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | バージョン ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


アイテムのクラスを識別します。有効な値: '1' - 1C（小売）'2' - 2C（小売）'3' - エコノミー（小売）'5' - Deffered（小売）'8' - Premium（Network Access）'9' - Standard（Network Access）

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 項目のクラス |

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

