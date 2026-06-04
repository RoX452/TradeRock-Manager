# TradeRock Manager

<p align="center">
  <img src="screenshots/screenshot 1.png" width="280" alt="TradeRock UI">
</p>
<p align="center">
  <img src="screenshots/screenshot 2.png" width="500" alt="Feature 1">
  <img src="screenshots/screenshot 3.png" width="400" alt="Feature 2">
</p>
<p align="center">
  <img src="screenshots/screenshot 4.png" width="400" alt="Feature 3">
  <img src="screenshots/screenshot 5.png" width="400" alt="Feature 4">
</p>
<p align="center">
  <img src="screenshots/screenshot 6.png" width="600" alt="Overview">
</p>
Una herramienta avanzada para la gestión de riesgo y administración de operaciones en MetaTrader 5. 

Este repositorio funciona a modo de exhibición para documentar la arquitectura, las funcionalidades y la metodología de desarrollo del proyecto. Por motivos de propiedad intelectual, el código fuente original no está publicado.

## Características Principales

*   **Gestor Visual de Órdenes (Estilo TradingView):** 
    *   Sistema interactivo que permite arrastrar zonas gráficas en la pantalla para definir visualmente el punto de entrada, el Stop Loss y el Take Profit antes de ejecutar la orden.
    *   **Controles flotantes integrados:** Botones interactivos directamente en las líneas de la orden gráfica:
        *   **Confirmar (✔):** Ejecuta la orden en el mercado con los parámetros visuales.
        *   **Cancelar (✕):** Elimina las líneas del gráfico.
        *   **Ancla (⚓):** Activa el modo imán para pegar el precio de entrada al precio actual del mercado.
        *   **Candado (🔒):** Bloquea el ratio Riesgo/Beneficio (RR) para que al mover el Stop Loss, el Take Profit se ajuste automáticamente manteniendo la proporción.
        *   **Revertir (↻):** Voltea la dirección de la operación gráfica de Compra a Venta o viceversa.
*   **Cálculo Automático de Lotes:** El sistema ajusta el tamaño de la posición automáticamente en base al riesgo establecido por el usuario y la distancia del Stop Loss.
*   **Panel de Control (UI):** Interfaz gráfica principal intuitiva y minimizable para controlar todos los parámetros de riesgo.
*   **Mini Panel de Historial:** Interfaz secundaria interactiva que muestra el registro y rendimiento (P&L) de las últimas operaciones y posiciones abiertas directamente en el gráfico.
*   **Gestión Dinámica de la Posición:**
    *   **Auto Break-Even:** Movimiento automático del Stop Loss al punto de entrada tras alcanzar un objetivo.
    *   **Cierres Parciales:** Configuración para cerrar porcentajes de la posición en diferentes niveles de ganancia.
    *   **Trailing Stop:** Seguimiento del precio para asegurar ganancias conforme la posición avanza a favor.
*   **Diseño Modular:** Arquitectura de código dividida en componentes independientes.

## Capturas de Pantalla

En la carpeta `screenshots/` se pueden visualizar ejemplos de la interfaz gráfica del panel y el sistema de gestión de riesgo funcionando directamente sobre el gráfico.
