---
title: "Aspose::BarCode::Metered clase"
linktitle: "Medido"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Metered clase. Proporciona métodos para establecer la clave medida en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode/metered/
---
## Metered class


Proporciona métodos para establecer la clave medida.

```cpp
class Metered : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Obtiene crédito de consumo |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |
| [GetProductName](./getproductname/)() | Obtiene el nombre del producto licenciado |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Verifica si el medido está licenciado |
| [Metered](./metered/)() | Inicializa una nueva instancia de esta clase. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Establece la clave pública y privada medida. Si usted compra una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, esto es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar ese caso, debe comprobar regularmente el estado de la licencia, y si está en estado de evaluación, llamar a esta API nuevamente. |
## Observaciones


En este ejemplo, se intentará establecer la clave pública y privada medida

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> el archivo jar del componente:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Ver también

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
