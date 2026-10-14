# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · Español · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

Documentación oficial y soporte de la comunidad para **Mole for Mac** y **Mole for Windows**.

Las apps para Mac y Windows son aplicaciones de escritorio nativas de pago, y la compra de licencias ayuda a financiar el desarrollo y las actualizaciones. Este repositorio es para documentación, preguntas y comentarios, y no contiene el código fuente de las apps. El [Mole CLI](https://github.com/tw93/Mole) sigue siendo gratuito y de código abierto.

## Descargar Mole

| App | Requisitos | Descarga | Guía de uso |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 o posterior, Apple Silicon o Intel | [Web para Mac](https://mole.fit/es/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Ayuda para Mac](https://mole.fit/es/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 o Windows 11, x64 o ARM64 | [Web para Windows](https://mole.fit/es/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Ayuda para Windows](https://mole.fit/es/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Las dos apps reúnen en una sola interfaz la limpieza, la gestión de apps, el mantenimiento, el análisis del disco y el estado del sistema en tiempo real.

### Mole for Mac

Mole for Mac es una app nativa en SwiftUI creada y mantenida por [Tw93](https://github.com/tw93), con herramientas rápidas en la barra de menús.

![Pantalla de limpieza de Mole for Mac](https://mole.fit/img/es/clean.jpg)

| Herramienta | Qué puedes hacer | Guía |
| --- | --- | --- |
| Limpiar | Revisa cachés de apps y navegadores, registros y archivos de compilación de desarrollo antes de elegir qué eliminar | [Limpieza del Mac](https://mole.fit/es/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Apps | Desinstala apps, revisa sus restos, busca actualizaciones y gestiona los elementos de inicio | [Gestión de apps](https://mole.fit/es/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Optimizar | Ejecuta el mantenimiento de macOS, usa Limpiar pantalla o Pantalla encendida | [Mantenimiento del Mac](https://mole.fit/es/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analizar | Encuentra archivos y carpetas grandes con un treemap del disco, muéstralos en Finder o mueve los elementos seleccionados a la Papelera | [Análisis del disco](https://mole.fit/es/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Estado | Consulta CPU, memoria, almacenamiento, red y temperatura, con las métricas que elijas en la barra de menús | [Monitor del sistema](https://mole.fit/es/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### Limpieza con IA · Preview

La versión Preview añade Limpieza y cuidado con IA dentro de Limpiar. Revisa cachés, versiones antiguas, sesiones antiguas, worktrees limpiables y herramientas de línea de comandos inactivas de Claude Code, Codex, Cursor y otras herramientas de IA. Las cachés aparecen seleccionadas, mientras que las sesiones y las herramientas requieren tu revisión. Los recuerdos, planes y skills quedan excluidos. Con los modelos locales, solo se listan los modelos de Ollama sin usar desde hace un mes, para que los selecciones y los elimines a través de Ollama. Consulta la [guía de limpieza con IA](https://mole.fit/es/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai) para más detalles.

### Empezar en tu Mac

1. Descarga el DMG desde la web para Mac de arriba, arrastra Mole a Aplicaciones y ábrelo. Si ya usas Homebrew, `brew install --cask mole-app` instala la app para Mac.
2. Haz un análisis y revisa los resultados antes de eliminar nada. Si Mole indica que falta el acceso total al disco, sigue la guía de permisos de abajo y vuelve a abrirlo.
3. Tras la compra, abre el panel de licencia con `Cmd + Shift + L`, pega la clave del correo de Dodo Payments y haz clic en Activar.

[Artículos para Mac](https://mole.fit/es/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notas de versión para Mac](https://mole.fit/es/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Guías seleccionadas para Mac

- [Mole CLI vs app para Mac](https://mole.fit/es/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): en qué se diferencian la herramienta gratuita de terminal y la app nativa de pago.
- [¿Es seguro Mole para Mac?](https://mole.fit/es/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): qué va a la Papelera, qué se elimina de forma permanente y qué queda protegido.
- [¿Qué son los datos del sistema en Mac?](https://mole.fit/es/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): encuentra qué ocupa espacio antes de borrar nada.
- [Revisar los restos de desinstalación en Mac](https://mole.fit/es/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): comprueba a quién pertenecen los archivos y los datos compartidos antes de eliminarlos.
- [Eliminar modelos de Ollama y LM Studio](https://mole.fit/es/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): separa los modelos descargados, las cachés y los datos personales.
- [Probar apps de Mac para Mole](https://mole.fit/es/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): qué revelan las instalaciones y desinstalaciones reales.

### Mole for Windows

La app para Windows mejora con cada versión.

![Pantalla de limpieza de Mole for Windows](https://mole.fit/img/windows-es/clean.jpg)

[Artículos para Windows](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notas de versión para Windows](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Comentarios

- [Informar de un error de la app para Mac](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Informar de un error de la app para Windows](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Sugerir una función](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Hacer una pregunta o unirte a una conversación](https://github.com/tw93/Mole-App/discussions)

Los issues y las conversaciones son públicos. Para consultas sobre compras, activación o reembolsos, escribe a [hi@mole.fit](mailto:hi@mole.fit). Envía los informes de seguridad por el [canal de informes privado](.github/SECURITY.md).

Para obtener diagnósticos en Mac, abre el menú del logotipo de Mole y elige Ejecutar Doctor. Envía el informe en privado a [hi@mole.fit](mailto:hi@mole.fit), junto con la versión de la app y lo que ocurrió.

Para errores y sugerencias del CLI, usa [tw93/Mole](https://github.com/tw93/Mole/issues).

## Preguntas frecuentes

### ¿Un repositorio público en GitHub significa que las apps son de código abierto?

Este repositorio contiene documentación y comentarios de la comunidad. El código fuente de las apps para Mac y Windows es privado. El [Mole CLI](https://github.com/tw93/Mole) es gratuito y de código abierto.

### ¿Necesito instalar el CLI para usar las apps?

No. Mole for Mac y Mole for Windows son apps de escritorio independientes. Instalar el CLI no instala ninguna de las dos.

### ¿Las apps son gratuitas?

Las apps usan licencias de pago único. Mole for Mac cuesta **$19 USD para dos Macs**, sin suscripción y con actualizaciones gratuitas, incluidas las versiones mayores. La [página oficial de precios](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) recoge las condiciones actuales. El precio y la disponibilidad de la versión para Windows están en su propia web. El CLI de código abierto es gratuito.

### ¿Puedo probar la app para Mac antes de comprarla?

El análisis es gratuito y cada herramienta de pago tiene dos usos de prueba. Puedes ver el análisis del disco y el estado del sistema sin licencia. El [centro de ayuda para Mac](https://mole.fit/es/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica cómo descargar, probar y activar la app.

### ¿Puedo pasar mi licencia de Mac a un ordenador nuevo?

Abre el panel de licencia en el Mac anterior con `Cmd + Shift + L`, desactívala y luego activa la misma clave en el Mac nuevo. Si ya no tienes el Mac anterior, inicia sesión en el [portal de clientes de Dodo Payments](https://customer.dodopayments.com/) con el correo de compra y desactívala desde allí. El límite de dispositivos depende de la licencia que compraste. La edición actual cubre dos Macs.

### ¿Dónde están mi clave de licencia y mi factura?

Busca Dodo Payments en tu bandeja de entrada y en la carpeta de spam, o inicia sesión en el [portal de clientes de Dodo Payments](https://customer.dodopayments.com/) con el correo usado al pagar para encontrar la clave, el pedido y la factura. Si aún necesitas ayuda, escribe a [hi@mole.fit](mailto:hi@mole.fit) con tu correo de compra o tu Payment ID. No publiques estos datos en issues públicos.

### ¿Y si la app para Mac no es lo que busco?

Escribe a [hi@mole.fit](mailto:hi@mole.fit) en los 14 días siguientes a la compra, con tu Payment ID o tu correo de compra. La [política de reembolso](https://mole.fit/es/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) recoge las condiciones completas.

### ¿La app para Mac sube mis archivos o los resultados del análisis?

El análisis y la limpieza se hacen en local, en tu Mac. Mole no sube el contenido ni los nombres de los archivos, ni los resultados del análisis, y su registro local de operaciones tampoco se sube de forma automática. La [política de privacidad](https://mole.fit/es/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica la activación de la licencia, las actualizaciones y otras funciones que contactan con servicios en línea.

### ¿Por qué Mole pide acceso total al disco?

macOS restringe el acceso a algunos datos de las apps. El acceso total al disco permite a Mole inspeccionar esas ubicaciones. Las rutas protegidas y tu lista blanca se siguen aplicando, así que conceder el acceso no convierte todos los archivos en candidatos a limpieza. Consulta la [guía de permisos](https://mole.fit/es/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### ¿Puedo recuperar archivos después de limpiar el Mac?

Las apps desinstaladas y los restos seleccionados van a la Papelera y se pueden recuperar mientras sigan allí. La limpieza de cachés es permanente por defecto, con una opción para usar la Papelera en Ajustes. Algunas acciones de mantenimiento eliminan datos directamente y no se pueden deshacer. La [guía de seguridad](https://mole.fit/es/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica cada operación.

### ¿Cómo funcionan las actualizaciones del Mac y las funciones Preview?

Mole tiene un actualizador integrado, y las [notas de versión oficiales](https://mole.fit/es/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) describen cada versión. Las funciones marcadas como Preview en la documentación requieren la versión Preview hasta que llegan a una versión estable.

### ¿Puedo usar Mole con el teclado o con VoiceOver?

Mole admite la navegación con teclado y VoiceOver. El treemap es visual, y puedes recorrer los mismos archivos en la lista de elementos más grandes con el teclado o VoiceOver. Consulta la [guía de accesibilidad](https://mole.fit/es/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) para ver los detalles y las limitaciones actuales.

### ¿Cuál es la web oficial?

**mole.fit** es la web oficial de las apps. Usa los enlaces de descarga de arriba para obtener los paquetes actuales. El CLI gratuito está en [tw93/Mole](https://github.com/tw93/Mole).

### ¿Dónde encuentro instrucciones detalladas?

La [documentación para Mac](https://mole.fit/es/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica las herramientas y sus reglas de seguridad. El [catálogo de apps probadas](https://mole.fit/es/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) incluye notas de instalación, desinstalación y restos de cada app. Para la configuración, la activación o la resolución de problemas, consulta el [centro de ayuda para Mac](https://mole.fit/es/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) o el [centro de ayuda para Windows](https://mole.fit/es/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). Las condiciones de la licencia están en los [términos del servicio](https://mole.fit/es/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
