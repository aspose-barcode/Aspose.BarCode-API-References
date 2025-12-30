---
title: AustraliaPostCustomerInformationDecoder
second_title: Aspose.BarCode for Android via Java API Reference
description: Public interface for Customer Information Field decoding which is used in AustraliaPost symbology.
type: docs
weight: 49
url: /androidjava/com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/
---```
public interface AustraliaPostCustomerInformationDecoder
```

Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. Implementation should be provided by user.
## Methods

| Method | Description |
| --- | --- |
| [decode(String customerInformationField)](#decode-java.lang.String-) | Decode Customer Information Field from AustraliaPost symbology. |
### decode(String customerInformationField) {#decode-java.lang.String-}
```
public abstract String decode(String customerInformationField)
```


Decode Customer Information Field from AustraliaPost symbology. Can be used for different data interpretation from NTable and CTable encoding. Data is provided as a row of bar values: 0, 1, 2 or 3. Example String[] N\_Table = \{ "00", "01", "02", "10", "11", "12", "20", "21", "22", "30" \}; public String decode(String customerInformationField) \{ StringBuilder bd = new StringBuilder(); for (int i = 0; customerInformationField.length > i; i += 2) \{ if (customerInformationField.length >= i + 2) \{ String tmp = customerInformationField.substring(i, i + 2); for (int j = 0; N\_Table.Length > j; j++) \{ if (N\_Table[j].equals(tmp)) \{ bd.append(j); break; \} \} \} \} return bd.toString(); \}

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customerInformationField | java.lang.String | The Customer Information Field encoded as row of raw bar values: 0, 1, 2 or 3 |

**Returns:**
java.lang.String - the decoded Customer Information Field string
