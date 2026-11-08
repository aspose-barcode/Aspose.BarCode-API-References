---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::FontUnit class. Define un formato particular para el texto, incluyendo la familia de fuente, el tamaño y los atributos de estilo donde el tamaño está en la propiedad de valor Unit en C++."
type: docs
weight: 2500
url: /es/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Define un formato particular para el texto, incluyendo la familia de fuente, el tamaño y los atributos de estilo donde el tamaño está en la propiedad de valor [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Obtiene el nombre de la familia de esta fuente. |
| [get_Size](./get_size/)() const | Obtiene el tamaño de este [FontUnit](./) en valor de [Unit](../unit/). |
| [get_Style](./get_style/)() const | Obtiene la información de estilo de este [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Establece el nombre de la fuente de este Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Establece la información de estilo de este [FontUnit](./). |
## Observaciones


Este ejemplo muestra cómo crear y guardar una imagen de [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
