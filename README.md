# Implementación de Estrategias Avanzadas de SEO en una Aplicación Angular

El equipo de desarrollo de una plataforma de comercio electrónico basada en Angular necesita mejorar su visibilidad en los motores de búsqueda. Para lograrlo, se requiere implementar varias estrategias avanzadas de SEO técnico, incluyendo la gestión de la etiqueta noindex, la configuración del archivo robots.txt, la creación de sitemaps XML y la integración de schemas.org. El objetivo es asegurar que la aplicación sea más amigable para los motores de búsqueda, mejorando así su ranking y atrayendo más tráfico orgánico.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Configuración SEO |
| **Nivel** | senior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 4-5 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración Inicial

**Objetivo:** Configurar la aplicación para que los motores de búsqueda la indexen correctamente.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identificar las páginas que no deben ser indexadas y aplicar la etiqueta noindex.
- Crear y configurar el archivo robots.txt para controlar el acceso de los motores de búsqueda a la aplicación.

**Entregable:** Aplicación configurada con la etiqueta noindex y el archivo robots.txt.

<details>
<summary>Pistas de conocimiento</summary>

- La etiqueta noindex previene que una página sea indexada por los motores de búsqueda.
- El archivo robots.txt guía a los motores de búsqueda sobre qué partes del sitio pueden o no ser rastreadas.

</details>

### Fase 2: Creación de Sitemaps XML

**Objetivo:** Generar sitemaps XML para mejorar la indexación de la aplicación por los motores de búsqueda.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Crear un sitemap XML que incluya todas las URLs de la aplicación.
- Asegurar que el sitemap esté correctamente enlazado en el archivo robots.txt.

**Entregable:** Sitemap XML generado y enlazado en el archivo robots.txt.

<details>
<summary>Pistas de conocimiento</summary>

- Los sitemaps XML ayudan a los motores de búsqueda a descubrir y rastrear todas las URLs de una aplicación.
- El sitemap debe estar enlazado en el archivo robots.txt para que los motores de búsqueda lo encuentren.

</details>

### Fase 3: Integración de Schemas.org

**Objetivo:** Integrar schemas.org en la aplicación para mejorar la representación de los datos en los resultados de búsqueda.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Identificar los tipos de datos que se pueden mejorar con schemas.org en la aplicación.
- Aplicar los esquemas adecuados para mejorar la representación de los datos en los resultados de búsqueda.

**Entregable:** Aplicación con schemas.org integrados para mejorar la representación de los datos.

<details>
<summary>Pistas de conocimiento</summary>

- Los schemas.org proporcionan una forma estandarizada de describir los datos en una página web.
- La integración de schemas.org puede mejorar la representación de los datos en los resultados de búsqueda, incluyendo rich snippets y otros elementos visuales.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es la etiqueta noindex y cómo se utiliza en una aplicación Angular para mejorar el SEO?
- **comoSeUsa**: ¿Cómo se crea y configura un sitemap XML en una aplicación Angular y por qué es importante para el SEO?
- **queDecisionesImplica**: ¿Qué decisiones debes tomar al integrar schemas.org en una aplicación Angular para mejorar la representación de los datos en los resultados de búsqueda?

## Criterios de Evaluacion

- Configuración correcta de la etiqueta noindex en las páginas adecuadas.
- Creación y configuración correcta del archivo robots.txt.
- Generación y enlazado correcto del sitemap XML.
- Integración adecuada de schemas.org para mejorar la representación de los datos en los resultados de búsqueda.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
