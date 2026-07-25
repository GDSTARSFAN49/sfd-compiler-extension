# **SFD Compiler**

Una herramienta imprescindible para los creadores de mapas y scripts de **Superfighters Deluxe (SFD)** (en verdad es solo para ayudar un poco xd, la pantalla del SFD para scripts es muy zzz). 

Esta extensión transforma VSCodium/VS Code en un entorno de desarrollo completo para SFD, ofreciendo autocompletado nativo, resaltado de sintaxis y un compilador en la nube que valida tu código en tiempo real sin que tengas que instalar el pesado SDK de .NET en tu ordenador.

# **IMPORTANTE**
Este "compilador/linter" no funciona de manera dinámica. Es decir, que mientras escribes, **no detectará fallos**. Para ello, cada vez que edites algo, **guarda tu archivo (Ctrl + s)** y verás ahí los errores que detecte el compilador. Si ves que no sale nada, **espera unos segundos*, ya que Render estará levantando el servidor (cosas de servicios gratis xd).

## **Características principales**

*   **Linter en la nube:** Cada vez que guardas tu script (`Ctrl + S`), la extensión se conecta de forma invisible a una API que utiliza el compilador oficial Roslyn y la `.dll` nativa del juego. Si tienes un error de sintaxis, lo verás subrayado en rojo de inmediato.
*   **Prevención de Typos:** Detecta si has escrito mal un evento oficial del juego (por ejemplo, escribir `AfterStartu` en lugar de `AfterStartup`) para que no subas scripts rotos al mapa.
*   **IntelliSense para SFD:** Autocompletado integrado. Solo escribe `Game.` y tendrás a tu disposición todas las clases, métodos y eventos oficiales del motor.
*   **Formato nativo (`.sfde`):** Introduce la extensión de archivo `.sfde` (Superfighters Deluxe Extension) con su propio icono y colores heredados de C# para una lectura perfecta.

## **Cómo usarlo**

1. Instala la extensión.
2. Crea un archivo y nómbralo con la extensión `.sfde` (por ejemplo, `metiche_abre_server.sfde`).
3. Empieza a escribir tu código. Notarás que el autocompletado de SFD ya está activo.
4. Guarda el archivo. Si no salen errores, tu código es 100% válido para pegarlo en el editor del juego.

## **Requisitos**

Ninguno.

## **Notas de la comunidad**

Esta extensión fue diseñada pensando en la comodidad... En verdad no sabia que hacer y dije hagamos esto y ya xd.

**`METICHE ABRE SERVER 🗣️🔥🔥🔥`**