# Metadata
¿Qué es un metadata y cómo utilizarlo en Next.js?

Los metadatos en el navegador sirven para optimizar el SEO, mejorar la visualización en redes sociales, y definir recursos como CSS y 
JavaScript, ayudando a que los navegadores y motores de búsqueda comprendan y presenten mejor la página web.

**Ejemplos de metadatos:**
- Meta etiquetas (`<meta>`)
- Título (`<title>`)
- SEO (optimización en motores de búsqueda)
- Open Graph
- Twitter Cards
- Recursos externos (CSS, JavaScript)
- Descripción de la página

### Código en Next.js:

```ts
import { Metadata } from "next";

export const metadata: Metadata = {
  title: 'SEO Title',
  description: 'SEO Title',
};
