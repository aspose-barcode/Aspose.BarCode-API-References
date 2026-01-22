---
title: Aspose::BarCode::Metered class
linktitle: Metered
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Metered class. Provides methods to set metered key in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode/metered/
---
## Metered class


Provides methods to set metered key.

```cpp
class Metered : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Gets consumption file size |
| [GetProductName](./getproductname/)() | Gets name of licensed product |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Check whether metered is licensed |
| [Metered](./metered/)() | Initializes a new instance of this class. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
## Remarks


In this example, an attempt will be made to set metered public and private key

<ms> 
```cpp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```
 </ms>

<java> the component jar file: 
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
 </java>
## See Also

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
