---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle classe"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle classe. Memorizza un insieme di quattro Points che rappresentano una regione Quadrangle in C++."
type: docs
weight: 3000
url: /it/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Memorizza un insieme di quattro [Point](../)s che rappresentano una regione [Quadrangle](./).

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Determina se il [Point](../) specificato è contenuto all'interno di questa classe [Quadrangle](./). |
| [Contains](./contains/)(int32_t, int32_t) | Determina se il punto specificato è contenuto all'interno di questa classe [Quadrangle](./). |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Determina se il [Quadrangle](./) specificato è contenuto o interseca questa classe [Quadrangle](./). |
| [Contains](./contains/)(System::Drawing::Rectangle) | Determina se il [Rectangle](../) specificato è contenuto o interseca questa classe [Quadrangle](./). |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [Quadrangle](./) specificato. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Ottiene il [Rectangle](../) che delimita questo [Quadrangle](./). |
| [get_IsEmpty](./get_isempty/)() | **Tests** se tutti i [Point](../) di questo [Quadrangle](./) hanno valori zero. |
| [get_LeftBottom](./get_leftbottom/)() const | Ottiene il punto [Point](../) dell'angolo in basso a sinistra della regione [Quadrangle](./). |
| [get_LeftTop](./get_lefttop/)() const | Ottiene il punto [Point](../) dell'angolo in alto a sinistra della regione [Quadrangle](./). |
| [get_RightBottom](./get_rightbottom/)() const | Ottiene il punto [Point](../) dell'angolo in basso a destra della regione [Quadrangle](./). |
| [get_RightTop](./get_righttop/)() const | Ottiene il punto [Point](../) dell'angolo in alto a destra della regione [Quadrangle](./). |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [Quadrangle](./quadrangle/)() | Inizializza una nuova istanza vuota della classe [Quadrangle](./). |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Inizializza una nuova istanza della classe [Quadrangle](./) con i punti descrittivi. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Ottiene il punto [Point](../) dell'angolo in basso a sinistra della regione [Quadrangle](./). |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Ottiene il punto [Point](../) dell'angolo in alto a sinistra della regione [Quadrangle](./). |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Ottiene il punto [Point](../) dell'angolo in basso a destra della regione [Quadrangle](./). |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Ottiene il punto [Point](../) dell'angolo in alto a destra della regione [Quadrangle](./). |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [Quadrangle](./). |
## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Rappresenta una classe [Quadrangle](./) con le sue proprietà lasciate non inizializzate. |
## Vedi anche

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
