---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::ITFParameters class. Parametri ITF in C++."
type: docs
weight: 3300
url: /it/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Parametri ITF.

```cpp
class ITFParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Ottiene lo spessore di un bordo ITF (barra di supporto) in valore [Unit](../unit/). Valore predefinito: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Tipo di bordo del codice a barre ITF. Valore predefinito: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Imposta lo spessore del bordo ITF (barra portante) in valore [Unit](../unit/). Valore predefinito: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Tipo di bordo del codice a barre ITF. Valore predefinito: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [ITFParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
