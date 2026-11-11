# Inventario POO

Aplicación web de gestión de inventario desarrollada en JavaScript aplicando los conceptos de Programación Orientada a Objetos vistos en la unidad 4.

## Autora

**Ana Isabel Chiquillo**
Estudiante de segundo semestre de Ingeniería de Software
Universidad de Cartagena

## Descripción

Permite registrar productos de distintos tipos, buscarlos, eliminarlos y consultar su precio final y el valor total del inventario. Los datos se guardan en el navegador.

## Conceptos de POO aplicados

- **Clases y objetos:** `Producto`, `ProductoPerecedero`, `ProductoElectronico`, `Inventario` y `Aplicacion`.
- **Clase principal:** `Aplicacion` controla el flujo y conecta la interfaz con la lógica.
- **Herencia:** `ProductoPerecedero` y `ProductoElectronico` extienden a `Producto`.
- **Polimorfismo:** los métodos `calcularPrecioFinal()` y `detalle()` se sobrescriben en cada subclase.
- **Encapsulamiento:** atributos privados (`#`) con getters y setters que validan los datos.

## Reglas de precio

- Todos los productos incluyen IVA del 19 %.
- **Perecederos:** 30 % de descuento si vencen en 3 días o menos; los vencidos no se pueden vender.
- **Electrónicos:** 3 % adicional por cada 12 meses de garantía.

## Cómo ejecutarla

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en cualquier navegador.

No requiere instalación ni dependencias.

## Tecnologías

HTML, CSS y JavaScript (ES6+).

## Contexto académico

Actividad "Desarrollo de una aplicación utilizando POO" (unidad 4), Universidad de Cartagena.
