# 💳 Simulador de Compras con Tarjeta de Crédito en Java

Este proyecto permite simular el comportamiento de una tarjeta de crédito a través de una aplicación de consola desarrollada en Java. El usuario establece un límite de crédito, registra compras con descripción y valor, y visualiza las transacciones ordenadas por monto.

---

## 🚀 Funcionalidades principales

- Establecer el límite de la tarjeta de crédito.
- Registrar compras con nombre y valor.
- Validar si una compra puede realizarse con el saldo disponible.
- Mostrar lista de compras realizadas, ordenadas por valor.
- Visualizar el saldo restante tras las transacciones.

---

## 🧩 Estructura del proyecto

```text
src/
├── Principal.java           // Flujo de ejecución principal
├── Compra.java              // Modelo de compra
└── TarjetaDeCredito.java    // Modelo de tarjeta con saldo y lista de compras
