# Metodología de Desarrollo y Uso de IA

Para construir este sistema en MetaTrader 5, decidí no programar todo desde cero línea por línea de la forma tradicional. En su lugar, me apoyé en herramientas basadas en agentes de Inteligencia Artificial (específicamente Antigravity) para ayudarme a estructurar el código y desarrollar los componentes.

## ¿Cómo usé la IA en este proyecto?

### 1. Definición de la Estructura
Antes de escribir el código, utilicé la IA para diseñar la arquitectura del programa. Le di instrucciones claras para que separara el proyecto en partes más pequeñas y manejables (módulos). Por ejemplo, le indiqué que separara la parte que dibuja la interfaz (UI) de la parte que ejecuta las compras y ventas en el mercado.

*Ejemplo del tipo de instrucción que usé:*
> "Vamos a crear un gestor de riesgo para MT5. Necesito que dividamos el sistema: una clase independiente para controlar las operaciones y otra para la interfaz gráfica. Dame primero el esqueleto de las clases antes de escribir las funciones."

### 2. Desarrollo por Módulos
En lugar de pedirle a la IA que "hiciera el bot", trabajamos componente por componente. Yo guiaba a la IA detallando exactamente qué debía hacer cada función, y luego yo me encargaba de probar e integrar esas piezas en el sistema principal.

*Ejemplo de instrucción:*
> "Revisa el archivo de la interfaz. Agrega tres botones para calcular el riesgo rápido (1%, 2%, 3%). Asegúrate de que al hacer clic no se bloquee el gráfico principal."

### 3. Apoyo con Scripts en Python y C#
Para algunas tareas muy repetitivas (como actualizar los botones de la interfaz o arreglar bloques grandes de código), me apoyé en la IA para crear pequeños scripts en Python. Estos scripts me ayudaron a modificar el código fuente de MQL5 de forma automática, ahorrándome horas de trabajo manual.

## Conclusión

El uso de asistentes de IA como herramientas de apoyo me permitió actuar más como un director del proyecto. Yo establecí las reglas, la lógica de trading y la arquitectura, y utilicé a los agentes de IA para materializar el código, refactorizarlo y armar la interfaz visual de forma mucho más rápida y limpia.
