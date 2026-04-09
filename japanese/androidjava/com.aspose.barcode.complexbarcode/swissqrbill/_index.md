---
title: SwissQRBill
second_title: Aspose.BarCode for Android via Java API Reference
description: SwissQR 請求書データ
type: docs
weight: 36
url: /ja/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR 請求書データ
## Methods

| Method | Description |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | 代替支払スキームを取得または設定します。 |
| [getAmount()](#getAmount--) | 支払金額を取得します。 |
| [getBillInformation()](#getBillInformation--) | 追加の構造化請求情報を取得します。 |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | 債権者の住所を取得します。 |
| [getCurrency()](#getCurrency--) | 支払通貨を取得します。 |
| [getDebtor()](#getDebtor--) | 債務者の住所を取得します。 |
| [getReference()](#getReference--) | 債権者の支払参照を取得します。 |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | 追加の非構造化メッセージを取得します。 |
| [getVersion()](#getVersion--) | SwissQR請求書標準のバージョンを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | 債権者の口座番号を設定します。 |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | 代替支払スキームを取得または設定します。 |
| [setAmount(double value)](#setAmount-double-) | 支払金額を設定します。 |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 追加の構造化請求情報を設定します。 |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | 債権者の住所を設定します。 |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | 支払通貨を設定します。 |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | 債務者の住所を設定します。 |
| [setReference(String value)](#setReference-java.lang.String-) | 債権者の支払参照を設定します。 |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 追加の非構造化メッセージを設定します。 |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | SwissQR請求書標準のバージョンを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

参照から空白が除去されます

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawReference | java.lang.String | 生の参照です。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 現在のオブジェクトと比較するオブジェクト。 |

**Returns:**
boolean - 指定されたオブジェクトが現在のオブジェクトと等しい場合は true、そうでない場合は false。
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。口座番号内のスペースは許可されます。

値: 債権者の口座番号です。

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


代替支払スキームを取得または設定します。

パラメータ付きスキームは最大で2つまで許可されます。

値: 代替支払スキームです。

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


支払金額を取得します。

有効な値は 0.01 から 999,999,999.99 の間です。

値: 支払金額。

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


追加の構造化請求情報を取得します。

値: 構造化請求情報。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


債権者の住所を取得します。

値: 債権者住所。

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


支払通貨を取得します。

有効な値は "CHF" と "EUR" です。

値: 支払通貨。

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


債務者の住所を取得します。

債務者は任意です。省略した場合、このフィールドを `null` に設定するか、すべての `null` または空の値を持つ住所を設定するかのどちらでも構いません。

値: 債務者住所。

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


債権者の支払参照を取得します。

SwissQR IBAN の場合、参照は必須です。すなわち、CHxx30000xxxxxx から CHxx31999xxxxx の範囲の IBAN です。

指定された場合、参照は有効な SwissQR 参照（ISR 参照形式に相当）または ISO 11649 に準拠した有効な債権者参照（"RFxxxx"）のいずれかでなければなりません。どちらも書式設定のためにスペースを含むことがあります。

値: 債権者支払参照。

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


追加の非構造化メッセージを取得します。

値: 非構造化メッセージ。

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


SwissQR請求書標準のバージョンを取得します。

値: SwissQR 請求書標準バージョン。

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを取得します。

**Returns:**
int - 現在のオブジェクトのハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


債権者の口座番号を設定します。

口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。口座番号内のスペースは許可されます。

値: 債権者の口座番号です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


代替支払スキームを取得または設定します。

パラメータ付きスキームは最大で2つまで許可されます。

値: 代替支払スキームです。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


支払金額を設定します。

有効な値は 0.01 から 999,999,999.99 の間です。

値: 支払金額。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


追加の構造化請求情報を設定します。

値: 構造化請求情報。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


債権者の住所を設定します。

値: 債権者住所。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


支払通貨を設定します。

有効な値は "CHF" と "EUR" です。

値: 支払通貨。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


債務者の住所を設定します。

債務者は任意です。省略した場合、このフィールドを `null` に設定するか、すべての `null` または空の値を持つ住所を設定するかのどちらでも構いません。

値: 債務者住所。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


債権者の支払参照を設定します。

SwissQR IBAN の場合、参照は必須です。すなわち、CHxx30000xxxxxx から CHxx31999xxxxx の範囲の IBAN です。

指定された場合、参照は有効な SwissQR 参照（ISR 参照形式に相当）または ISO 11649 に準拠した有効な債権者参照（"RFxxxx"）のいずれかでなければなりません。どちらも書式設定のためにスペースを含むことがあります。

値: 債権者支払参照。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


追加の非構造化メッセージを設定します。

値: 非構造化メッセージ。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


SwissQR請求書標準のバージョンを設定します。

値: SwissQR 請求書標準バージョン。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

