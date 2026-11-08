---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class. Representa la región del código de barras reconocido y el ángulo del código de barras en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Representa la región del código de barras reconocido y el ángulo del código de barras

```cpp
class BarCodeRegionParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Angle](./get_angle/)() const | Obtiene el ángulo del código de barras (0-360). |
| [get_Points](./get_points/)() const | Obtiene la matriz de [Point](../)s que delimitan la región del código de barras |
| [get_Quadrangle](./get_quadrangle/)() const | Obtiene el [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) que delimita la región del código de barras |
| [get_Rectangle](./get_rectangle/)() const | Obtiene **System::Drawing::Rectangle** que delimita la región del código de barras |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [BarCodeRegionParameters](./). |
## Observaciones


Este ejemplo muestra cómo obtener el ángulo del código de barras y los valores del cuadrilátero delimitador
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
