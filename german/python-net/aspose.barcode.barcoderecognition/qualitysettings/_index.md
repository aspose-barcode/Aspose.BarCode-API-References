---
title: "QualitySettings"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren.<br/>            Sie können QualitySettings schnell mit eingebetteten Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxQuality oder Sie können einzelne Optionen manuell konfigurieren.<br/>            Der Standardwert von QualitySettings ist NormalQuality.

Der **QualitySettings**-Typ stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| high_performance | HighPerformance-Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus gut erkannt. |
| normal_quality | NormalQuality-Erkennungsqualitäts-Voreinstellung. Geeignet für die meisten Barcodes |
| high_quality | HighQuality-Erkennungsqualitäts-Voreinstellung. Diese Voreinstellung ist für Barcodes niedriger Qualität entwickelt. Ermöglicht das Erkennen stark beschädigter Barcodes. |
| max_quality | MaxQuality-Erkennungsqualitäts-Voreinstellung. Diese Voreinstellung ist entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes. |
| x_dimension | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich. |
| minimal_x_dimension | Minimale Größe von XDimension in Pixeln, die zusammen mit UseMinimalXDimension verwendet wird. |
| barcode_quality | Modus, der Methoden aktiviert, um Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, was die Erkennung verlangsamt. |
| deconvolution | Deconvolution (Bildwiederherstellung) Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein degradierte <br/>            (konvolutierte) Bilder durch jede natürliche Funktion wie Unschärfe wiederherstellen kann, die beim Aufnehmen des Bildes mit der Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, <br/>            müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen. |
| inverse_image | Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| complex_background | Modus, der die zusätzliche Erkennung von Farbbarcodes auf Farbbildern aktiviert oder deaktiviert. |
| allow_incorrect_barcodes | Ermöglicht der Engine, Barcodes mit falscher checksumm oder falschen Werten zu erkennen. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen. |

### Siehe auch

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

