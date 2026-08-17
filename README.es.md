<p align="center">
  <a href="https://dshplugin.dev/">
    <img src="https://dshplugin.dev/assets/dsh-plugin-icon-192.png" width="96" height="96" alt="Logo de dshplugin.dev" />
  </a>
</p>

# Awesome DSH Plugin

<p align="center"><strong>Manual de producto y navegador de plugins para usuarios de DeepSeek Harness.</strong></p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.zh-CN.md">简体中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <strong>Español</strong>
</p>

Comprueba para qué sirve un plugin y qué permisos necesita. Después, consulta su ficha completa en [dshplugin.dev](https://dshplugin.dev/). También puedes hacer clic en el logo para visitar el sitio web.

[![Website](https://img.shields.io/badge/Explorar-dshplugin.dev-0B6E5F)](https://dshplugin.dev/)
[![Baseline](https://img.shields.io/badge/Base_pública_controlada-87-2563EB)](https://dshplugin.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Para qué sirve este manual

DeepSeek Harness, también llamado DSH, sigue el modelo “Everything is a Plugin”. Los plugins de la comunidad pueden añadir herramientas de desarrollo, automatización, interacción con el navegador, diseño de interfaces, gestión de sesiones, conexiones con modelos, controles de seguridad y almacenamiento.

Este repositorio está pensado para quienes quieren utilizar esos productos. No es una referencia de API, una guía de arquitectura ni documentación para desarrollar plugins. Su objetivo es responder cuatro preguntas prácticas:

1. ¿Qué tipo de plugin encaja con mi objetivo?
2. ¿Qué debo revisar antes de instalarlo?
3. ¿Dónde puedo consultar la información más reciente?
4. ¿Qué hago si aparecen problemas de permisos o compatibilidad?

Cada plugin publicado abre una ficha interna de `dshplugin.dev`. El repositorio también hace visibles los 1.488 registros de la instantánea del 17 de agosto de 2026, incluidos los candidatos y los registros no publicados. Solo las 87 páginas de la base pública verificada reciben un enlace a su ficha, para no confundir visibilidad con publicación o recomendación.

> [!IMPORTANT]
> `dshplugin.dev` es un directorio comunitario independiente, no un sitio oficial de DeepSeek. La inclusión de un proyecto no representa una recomendación de DeepSeek ni del editor. Un repositorio público, el número de estrellas o una actualización reciente no demuestran por sí solos seguridad, compatibilidad o calidad de mantenimiento.

## Empieza aquí

| Lo que quieres hacer | Página recomendada |
| --- | --- |
| Buscar por nombre o caso de uso | [Directorio completo](https://dshplugin.dev/) |
| Instalar un plugin de DSH por primera vez | [Guía de instalación y verificación](https://dshplugin.dev/guides/install-deepseek-harness-plugins) |
| Ver proyectos admitidos recientemente en el catálogo público | [Nuevos plugins](https://dshplugin.dev/collections/new-releases) |
| Encontrar proyectos con actualizaciones recientes | [Actualizados recientemente](https://dshplugin.dev/collections/recently-updated) |
| Usar las estrellas de GitHub como señal inicial | [Con más estrellas](https://dshplugin.dev/collections/most-starred) |
| Explorar por autor o equipo | [Directorio de editores](https://dshplugin.dev/publishers) |
| Entender las reglas de inclusión y corrección | [Política editorial](https://dshplugin.dev/editorial-policy) |
| Consultar el tamaño y las categorías del ecosistema | [Informe del ecosistema](https://dshplugin.dev/reports/deepseek-harness-plugin-ecosystem) |

## Inventario completo del ecosistema

No se oculta ningún registro de la instantánea del 17 de agosto de 2026. Abre el [inventario completo](inventory/README.es.md) para consultar los **1.488 registros** según su estado de publicación:

| Inventario | Registros | Qué puedes hacer |
| --- | ---: | --- |
| Publicados | 87 | Abrir la ficha completa del plugin en `dshplugin.dev`. |
| Candidatos | 1.166 | Consultar nombre, categoría, resumen, lenguaje y licencia mientras esperan revisión humana. |
| En cuarentena | 216 | Ver los registros conservados para auditoría porque las pruebas disponibles son incompletas. |
| Rechazados | 19 | Ver los registros que no superaron una condición obligatoria de publicación. |

Los candidatos, los registros en cuarentena y los rechazados no pertenecen a la base pública controlada, por lo que no enlazan a fichas individuales. Algunas URL transitorias todavía pueden responder mientras se limpia el sitio web. Así se mantiene visible todo lo recopilado sin tratar páginas inestables como destinos publicados.

## Elige según tu necesidad

Los archivos de categoría forman el catálogo público navegable de 87 páginas. El [inventario completo](inventory/README.es.md) muestra por separado los 1.488 registros recopilados sin tratar cada hallazgo como publicado.

| Categoría | Úsala cuando necesites | Instantánea | Catálogo completo |
| --- | --- | ---: | --- |
| Developer Tools | Código, terminal, archivos, depuración, API o flujos locales | 46 | [Ver la base](catalog/developer-tools.md) |
| Automation | Tareas repetitivas, coordinación de agentes, flujos o integraciones | 10 | [Ver la base](catalog/automation.md) |
| Browser | Navegación, investigación, extracción, pruebas o conexión con el navegador | 9 | [Ver la base](catalog/browser.md) |
| UI & Design | Interfaces, temas, visualización, diseño o vistas previas | 6 | [Ver la base](catalog/ui-design.md) |
| Models | Adaptadores, enrutamiento, alternativas o proveedores de inferencia | 2 | [Ver la base](catalog/models.md) |
| Sessions | Historial, memoria, contexto, resúmenes o gestión de conversaciones | 9 | [Ver la base](catalog/sessions.md) |
| Security | Permisos, entornos aislados, políticas, secretos o controles defensivos | 5 | [Ver la base](catalog/security.md) |
| Storage | Persistencia, bases de datos, caché o almacenamiento de artefactos | 0 | [Ver el estado](catalog/storage.md) |

## Cómo funciona el estado de publicación

Descubrir un proyecto y publicarlo son decisiones distintas. El rastreador automático puede encontrar un candidato, pero no puede incorporarlo directamente a este catálogo público.

| Estado | Qué significa para el usuario |
| --- | --- |
| Base pública | Es el conjunto histórico de URL cuya indexación se verificó en Search Console. Se conservan los enlaces para mantener URL estables, pero esto no demuestra una revisión manual reciente ni una certificación de seguridad. |
| Candidate | Ha superado las comprobaciones automáticas iniciales y espera revisión humana. Aparece en el inventario completo, pero sin enlace a una ficha. |
| Quarantined | No hay pruebas suficientes para establecer que sea un plugin de DSH con funcionalidad sustancial. Aparece para fines de auditoría, pero queda fuera del catálogo público. |
| Rejected | Está archivado, no es accesible, está vacío o ha fallado una condición excluyente. Se conserva en el inventario de auditoría y un rastreo posterior no debe volver a publicarlo automáticamente. |

El informe del ecosistema puede mostrar más proyectos descubiertos o auditados que este catálogo. La diferencia es intencionada: se priorizan la calidad y una indexación estable frente a publicar todos los repositorios encontrados.

Categorías en el sitio web:

- [Developer Tools](https://dshplugin.dev/categories/developer-tools)
- [Automation](https://dshplugin.dev/categories/automation)
- [Browser](https://dshplugin.dev/categories/browser)
- [UI & Design](https://dshplugin.dev/categories/ui-design)
- [Models](https://dshplugin.dev/categories/models)
- [Sessions](https://dshplugin.dev/categories/sessions)
- [Security](https://dshplugin.dev/categories/security)
- [Storage](https://dshplugin.dev/categories/storage)

## Cómo usar plugins comunitarios con más seguridad

### 1. Ejecuta primero el Harness básico

Para la primera ejecución, inicia la Web UI con el comando indicado por el proyecto oficial:

```sh
npx @deepseek-ai/dsh web
```

La dirección predeterminada documentada es `http://127.0.0.1:3080`. Comprueba que el producto base funciona antes de añadir código de terceros. Así tendrás un punto de referencia limpio si algo falla después.

### 2. Revisa la ficha antes de instalar

Comprueba al menos lo siguiente:

- si el plugin resuelve realmente tu problema;
- si el comando completo procede de la documentación actual del editor;
- el profile de destino, la versión de DSH, el sistema operativo y los requisitos;
- la última actualización, los Issues abiertos y las notas de mantenimiento;
- si la licencia permite tu uso personal, de equipo o comercial;
- los servicios externos, cuentas, secretos o API de pago necesarios;
- si hay capturas, demostraciones o resultados reproducibles.

### 3. Revisa los permisos antes de concederlos

Un plugin es código de terceros. Detente y lee el código fuente y la explicación del editor si puede:

- leer o modificar archivos locales, o ejecutar comandos de terminal;
- controlar el navegador, leer páginas o usar una sesión autenticada;
- acceder a la red, subir contenido o llamar a API externas;
- leer variables de entorno, credenciales, sesiones o conversaciones;
- cambiar el enrutamiento de modelos, la política de aprobación o la seguridad.

Si la ficha no muestra un comando de instalación o una explicación de permisos, trátala como información de referencia. No inventes un comando a partir del nombre del repositorio.

### 4. Verifica una función cada vez

1. Conserva el profile, la rama, la etiqueta y la versión indicados por el editor.
2. Actualiza o reinicia el profile y comprueba que no haya errores de carga o aprobación.
3. Ejecuta el ejemplo más pequeño y reversible de la documentación.
4. Concede únicamente los permisos necesarios para esa función.
5. Guarda el repositorio y la revisión instalada para poder reproducir o revertir el cambio.

## Cómo comparar dos plugins

No decidas solo por el número de estrellas.

| Aspecto | Pregunta que debes hacerte |
| --- | --- |
| Ajuste a la necesidad | ¿Resuelve tu problema concreto o solo menciona DSH? |
| Claridad de instalación | ¿Incluye comando completo, profile y requisitos? |
| Compatibilidad | ¿Indica versiones de DSH, sistemas y limitaciones conocidas? |
| Alcance de permisos | ¿Los permisos son proporcionales a la función? |
| Evidencia comprobable | ¿Hay capturas, demostraciones, resultados o pasos de prueba? |
| Mantenimiento | ¿Hay actualizaciones, respuestas a Issues y avisos de cambios incompatibles? |
| Licencia | ¿Permite tu uso personal, de equipo o comercial? |
| Salida | ¿Se puede desactivar, eliminar o revertir con claridad? |

## Solución de problemas

### El plugin no aparece después de instalarlo

Comprueba de nuevo el profile, el paquete, la rama o la etiqueta. Después, busca errores de carga en la interfaz de Harness y en los Issues del editor. Instala un solo plugin cada vez para poder identificar qué cambio provocó el problema.

### Dejó de funcionar después de una actualización

DeepSeek Harness sigue cambiando rápidamente y el proyecto oficial avisa de posibles cambios incompatibles. Compara la versión de Harness, la última actualización del plugin y las notas de compatibilidad. Si es necesario, vuelve a una versión que hayas registrado como funcional.

### Solicita permisos muy amplios

No los apruebes inmediatamente. Confirma que cada permiso esté relacionado directamente con la función y revisa el código fuente, la justificación y el historial de Issues. No concedas acceso a archivos, navegador, red o secretos sin una explicación clara.

### ¿La inclusión equivale a recomendación o certificación?

No. La inclusión significa que el directorio encontró y normalizó información de fuentes públicas. No es una auditoría de seguridad, un certificado de compatibilidad, una garantía de calidad ni una recomendación oficial.

## Alcance de los datos y actualizaciones

- Fecha de la instantánea: 2026-08-17
- Instantánea de descubrimiento visible en este repositorio: 1.488 registros
- Base pública controlada en este repositorio: 87 páginas de plugins
- Colas de revisión: 1.166 candidatos, 216 en cuarentena y 19 rechazados
- Categorías con entradas en la base: 7; Storage tiene actualmente 0
- Fuentes: repositorios públicos de GitHub, metadatos de npm y páginas de los editores
- Estado actual: [Informe del ecosistema](https://dshplugin.dev/reports/deepseek-harness-plugin-ecosystem)
- Método de inclusión: [Política editorial](https://dshplugin.dev/editorial-policy)

Los nombres, descripciones, licencias y señales de actividad pueden cambiar. El inventario completo conserva la instantánea de auditoría; los archivos de categoría siguen siendo el catálogo navegable controlado. Para un plugin publicado, verifica el estado actual en la ficha del sitio web y en la fuente del editor.

## Enviar o corregir un plugin

Los autores pueden publicar un repositorio claro, añadir el topic `dsh-plugin` en GitHub y seguir la [guía de envío](https://dshplugin.dev/submit). El descubrimiento crea un candidato para revisión; no publica automáticamente una ficha.

Para informar de un error o un proyecto ausente, aporta fuentes públicas mediante la [página de contacto](https://dshplugin.dev/contact) o un Issue de este repositorio. Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para conocer las reglas.

## Independencia

Este repositorio y [dshplugin.dev](https://dshplugin.dev/) son proyectos comunitarios independientes. No están afiliados con DeepSeek ni cuentan con el respaldo de DeepSeek o de los editores incluidos. DeepSeek, DeepSeek Harness, los nombres de los plugins, los logos y las marcas pertenecen a sus respectivos propietarios.

## Licencia

[MIT](LICENSE)
