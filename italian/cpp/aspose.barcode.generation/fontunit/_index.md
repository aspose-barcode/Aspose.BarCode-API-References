---
title: "Aspose::BarCode::Generation::FontUnit classe"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::FontUnit classe. Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile dove la dimensione è nella proprietà valore Unit in C++."
type: docs
weight: 2500
url: /it/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile dove la dimensione è nella proprietà valore [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Ottiene il nome del tipo di carattere di questo Font. |
| [get_Size](./get_size/)() const | Ottiene la dimensione di questo [FontUnit](./) in valore [Unit](../unit/). |
| [get_Style](./get_style/)() const | Ottiene le informazioni di stile per questo [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Imposta il nome del carattere di questo Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Imposta le informazioni di stile per questo [FontUnit](./). |
## Osservazioni


Questo esempio mostra come creare e salvare un'immagine [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
