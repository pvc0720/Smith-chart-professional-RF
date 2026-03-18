# 📡 Carta de Smith — RF Pro

**Carta de Smith — RF Pro** es una herramienta interactiva y profesional que se ejecuta directamente en el navegador, diseñada para el análisis de circuitos de Radiofrecuencia (RF), adaptación de impedancias y visualización de parámetros en líneas de transmisión. 

Este proyecto fue desarrollado por **Pedro Andrés Viloria Colón**, estudiante de Ingeniería de Telecomunicaciones de la **Universidad de Antioquia**, con el propósito de facilitar cálculos avanzados y visualizaciones prácticas en el diseño y análisis de redes de RF.

🌍 **[Prueba la herramienta en vivo aquí](https://pvc0720.github.io/Smith-chart-professional-RF/)**

---

## 🛠️ Características Principales

* 📊 **Gráfico Interactivo Avanzado:** Trazado de puntos en la Carta de Smith renderizado en Canvas, con soporte para acercamiento (zoom) y visualización por capas (Admitancia, Ángulos Γ, ROE constante, etc.).
* 🔄 **Múltiples Modos de Entrada:** Calcula y plotea datos ingresando:
  * Impedancia $Z$ ($R+jX$)
  * Admitancia $Y$ ($G+jB$)
  * Coeficiente de Reflexión $\Gamma$ ($a+jb$)
  * Return Loss (dB)
  * Relación de Onda Estacionaria (ROE / VSWR)
* 📁 **Soporte Touchstone (.s1p):** Importa archivos de parámetros S11 (como barridos de antenas o redes) y visualiza la respuesta en frecuencia directamente en la carta y en formato tabular.
* 🧮 **Cálculos en Tiempo Real:**
  * Diagnóstico de adaptación y parámetros de línea: Mismatch Loss, Potencia reflejada/transmitida y ROE.
  * Extracción de componentes equivalentes ($L, C, Q$).
  * Cálculo rápido de impedancias conjugadas ($Z^*$).
* 💾 **Exportación de Datos:** Descarga tus puntos de análisis en formato **CSV**, o exporta el gráfico interactivo directamente como imagen **PNG** o vector **SVG** para informes académicos o profesionales.
* 🌙 **Interfaz Responsiva y Modo Oscuro:** Diseño moderno que se adapta a las preferencias del sistema (Light/Dark mode) para cuidar la vista en largas jornadas de análisis.
* ⚡ **Módulos Adicionales:** Incluye herramientas dedicadas para barrido en frecuencia, panel de ROE/RL, cálculos de línea de transmisión y acoples.

---

## 🚀 Cómo usar

1. Ingresa a la [página del proyecto](https://pvc0720.github.io/Smith-chart-professional-RF/).
2. Define la Impedancia Característica ($Z_0$) y la Frecuencia de trabajo (MHz) en la barra superior.
3. Selecciona tu "Modo" de entrada de datos y escribe los parámetros correspondientes.
4. Haz clic en **Ubicar** para trazar el punto en el plano. 
5. Explora el panel lateral para ver los **Resultados** detallados, gestionar tu lista de **Puntos**, importar un archivo **Touchstone** o modificar las **Capas** de visualización para ver círculos de ROE o admitancia.

---

## 💻 Desarrollo y Tecnologías

El proyecto funciona completamente del lado del cliente (*Client-Side*) sin depender de servidores externos para los cálculos, garantizando privacidad y un rendimiento instantáneo. 
* Construido con **HTML5** y **CSS3** puros.
* Lógica desarrollada en **JavaScript (Vanilla)** para el cálculo matemático con números complejos y el renderizado gráfico nativo.

---

## 👨‍💻 Autor

**Pedro Andrés Viloria Colón** *Ingeniería de Telecomunicaciones* *Universidad de Antioquia* Si encuentras útil la herramienta, tienes alguna sugerencia de mejora matemática o encuentras un *bug*, ¡no dudes en abrir un *Issue* en este repositorio!
