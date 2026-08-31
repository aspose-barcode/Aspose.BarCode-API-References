---
title:  method
linktitle: CleanValue
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Cleans a string value to make it viable for the Swiss Payment Standards 2018 in C++.'
type: docs
weight: 100
url: /cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Cleans a string value to make it viable for the Swiss Payment Standards 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::String | The string value to clean. |
| result | Payments::CleaningResult\& | The result to be filled with cleaned string and flag. |
## Remarks


Unsupported characters(according to Swiss Payment Standards 2018, ch. 2.4.1 and appendix D) are replaced with spaces(unsupported whitespace) or dots (all other unsupported characters). Leading and trailing whitespace is removed. 

If characters beyond 0xff are detected, the string is first normalized such that letters with umlauts or accents expressed with two code points are merged into a single code point(if possible), some of which might become valid. 

If the resulting strings is all white space, **null** is returned. 

## See Also

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
