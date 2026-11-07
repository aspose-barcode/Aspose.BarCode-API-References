---
title: "Methode"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Legt den nutzungsbasierten öffentlichen und privaten Schlüssel fest. Wenn Sie eine nutzungsbasierte Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Falls jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut in C++ auf."
type: docs
weight: 200
url: /de/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch das Hochladen der Verbrauchsdaten ständig fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | System::String | öffentlicher Schlüssel |
| privateKey | System::String | privater Schlüssel |

## Siehe auch

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
