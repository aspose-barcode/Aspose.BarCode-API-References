---
title: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality class"
linktitle: "Iso15416Quality"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality class. Almacena los grados de calidad del código de barras calculados según la norma ISO/IEC 15416 para códigos de barras 1D en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.barcode.barcoderecognition/iso15416quality/
---
## Iso15416Quality class


Almacena las calificaciones de calidad de códigos de barras calculadas según la norma ISO/IEC 15416 para códigos de barras 1D.

```cpp
class Iso15416Quality : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Decodability](./get_decodability/)() const | Obtiene el grado de decodificabilidad basado en la precisión de los anchos de barras y espacios. |
| [get_Decode](./get_decode/)() const | Obtiene el grado de decodificación que indica si el código de barras puede ser decodificado usando el algoritmo de decodificación de referencia. |
| [get_Defects](./get_defects/)() const | Obtiene el grado de defectos basado en irregularidades de reflectancia dentro de las barras y espacios. |
| [get_DetailedGrades](./get_detailedgrades/)() const | Obtiene grados de calidad adicionales, incluidos los controles específicos de la simbología. |
| [get_Grade](./get_grade/)() const | Obtiene el grado general de calidad del código de barras según ISO/IEC 15416. |
| [get_MinimumEdgeContrast](./get_minimumedgecontrast/)() const | Obtiene el grado mínimo de contraste de borde basado en la menor diferencia de reflectancia entre barras y espacios adyacentes. |
| [get_MinimumReflectance](./get_minimumreflectance/)() const | Obtiene el grado mínimo de reflectancia basado en la reflectancia de la barra más oscura. |
| [get_Modulation](./get_modulation/)() const | Obtiene el grado de modulación basado en la uniformidad del contraste de borde a lo largo del código de barras. |
| [get_SymbolContrast](./get_symbolcontrast/)() const | Obtiene el grado de contraste del símbolo basado en la diferencia entre la reflectancia máxima y mínima. |
## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
