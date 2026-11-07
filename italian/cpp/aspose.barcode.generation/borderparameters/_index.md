---
title: "Aspose::BarCode::Generation::BorderParameters classe"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::BorderParameters classe. Parametri del bordo dell'immagine del codice a barre in C++."
type: docs
weight: 800
url: /it/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Parametri del bordo dell'immagine del codice a barre

```cpp
class BorderParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Color](./get_color/)() const | Colore del bordo. Valore predefinito: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Stile di tratteggio del bordo. Valore predefinito: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Visibilità del bordo. Se false, il parametro Width viene sempre ignorato (0). Valore predefinito: false. |
| [get_Width](./get_width/)() const | Larghezza del bordo. Valore predefinito: 0. Ignorata se Visible è impostato su false. |
| [set_Color](./set_color/)(System::Drawing::Color) | Colore del bordo. Valore predefinito: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Stile di tratteggio del bordo. Valore predefinito: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Visibilità del bordo. Se false, il parametro Width viene sempre ignorato (0). Valore predefinito: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Larghezza del bordo. Valore predefinito: 0. Ignorata se Visible è impostato su false. |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile da un umano di questo [BorderParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
