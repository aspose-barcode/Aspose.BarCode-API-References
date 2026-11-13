---
title: "Metered"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode/metered/
---

## Metered class

Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit.

Der Typ Metered stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Metered() | Initialisiert eine neue Instanz der Klasse Metered |
## Methoden
| Name | Beschreibung |
| :- | :- |
| set_metered_key(public_key, private_key) | Setzt den öffentlichen und privaten Schlüssel für die nutzungsbasierte Lizenz.<br/>            Wenn Sie eine nutzungsbasierte Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. <br/>            Sollte jedoch stets das Hochladen der Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz in den Evaluierungsstatus versetzt, <br/>            um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
| get_consumption_quantity() | Liefert die Dateigröße des Verbrauchs |
| get_consumption_credit() | Liefert das Verbrauchsguthaben |
| get_product_name() | Liefert den Namen des lizenzierten Produkts |
| is_metered_licensed() | Prüft, ob die nutzungsbasierte Lizenz aktiv ist |

### Siehe auch

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

