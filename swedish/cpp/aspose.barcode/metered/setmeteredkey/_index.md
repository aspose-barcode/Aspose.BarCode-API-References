---
title: "metod"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ställer in mätad offentlig och privat nyckel. Om du köper en mätad licens, när du startar applikationen bör detta API anropas, normalt räcker detta. Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till evalueringsstatus. För att undvika ett sådant fall bör du regelbundet kontrollera licensstatusen; om den är i evalueringsstatus, anropa detta API igen i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Sätter mätad publik och privat nyckel. Om du köper en mätad licens, när du startar applikationen, bör detta API anropas, normalt räcker detta. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus; för att undvika ett sådant fall bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | System::String | offentlig nyckel |
| privateKey | System::String | privat nyckel |

## Se även

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
