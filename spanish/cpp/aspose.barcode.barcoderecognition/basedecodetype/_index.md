---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType clase"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType clase. Clase base para MultiDecodeType y SingleDecodeType en C++."
type: docs
weight: 900
url: /es/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Clase base para [MultiDecodeType](../multidecodetype/) y [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Determina si alguno de los tipos de decodificación dados está incluido en |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [SingleDecodeType](../singledecodetype/). |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [MultiDecodeType](../multidecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Devuelve un valor que indica si esta instancia es igual a un valor especificado de [BaseDecodeType](./). |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Convierte la representación en cadena de un [SingleDecodeType](../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Convierte la representación de cadena de un [MultiDecodeType](../multidecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Convierte la representación en cadena de un [BaseDecodeType](./) a su instancia, después de determinar el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló. |
## Observaciones


Este ejemplo muestra cómo usar [BaseDecodeType](./) con [SingleDecodeType](../singledecodetype/) y [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
