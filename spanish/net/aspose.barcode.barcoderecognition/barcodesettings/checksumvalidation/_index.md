---
title: "BarcodeSettings.ChecksumValidation"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarcodeSettings. Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales"
type: docs
weight: 30
url: /es/net/aspose.barcode.barcoderecognition/barcodesettings/checksumvalidation/
---
## BarcodeSettings.ChecksumValidation property

Habilita la validación de suma de verificación durante el reconocimiento para códigos de barras 1D y postales.

El valor predeterminado se trata como Sí para las simbologías que deben contener suma de verificación, y como No donde la suma de verificación solo es posible.

Suma de verificación nunca usada: Codabar, PatchCode, Pharmacode, DataLogic2of5

La suma de verificación es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Suma de verificación siempre utilizada: resto de simbologías

```csharp
public ChecksumValidation ChecksumValidation { get; set; }
```

### Property Value

Habilita la validación de suma de verificación durante el reconocimiento para códigos de barras 1D y postales.

## Ejemplos

Este ejemplo muestra la influencia de ChecksumValidation en la calidad y resultados del reconocimiento

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //suma de verificación desactivada
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //suma de verificación activada
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Ver también

* enum [ChecksumValidation](../../checksumvalidation/)
* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


