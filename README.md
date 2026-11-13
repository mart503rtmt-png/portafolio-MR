# Portafolio MR

Portafolio personal de **Marcos Reyes**, enfocado en **Front End y diseño de interfaces**. Primera versión: estructura funcional y hero.

## Ejecutar en local

No requiere instalar dependencias ni compilar. Con Python 3:

```bash
python3 -m http.server 8000 --directory dist
```

Abre http://localhost:8000. También puedes servir `dist/` con un servidor estático de tu editor.

## Archivos

- `dist/index.html`: contenido y estructura de las secciones.
- `dist/style.css`: diseño y adaptación a diferentes tamaños de pantalla.
- `.openai/hosting.json`: configuración del sitio existente en Sites. No contiene credenciales.
- `CONTRIBUTING.md`: flujo de práctica con ramas y pull requests.

## Dirección visual

Español; estética oscura, editorial y tecnológica, con maximalismo controlado y bastante aire. Negro, violeta y blanco/grises. Tipografías Syne, Space Grotesk y Geist Mono, servidas desde Google Fonts con alternativas de sistema.

## Apartados y ramas

| Apartado | Rama |
| --- | --- |
| Cabecera y navegación | `feature/navegacion` |
| Hero / presentación inicial | `feature/hero` |
| Proyectos principales: Portal Docente y Casa Artesanal | `feature/proyectos` |
| Sobre mí | `feature/sobre-mi` |
| Exploraciones: BioForce, Detector de microsismos, MiFeria y Servidor Ubuntu | `feature/exploraciones` |
| Pie de página | `feature/footer` |
| Contacto por WhatsApp Business | `feature/contacto` |

`main` conserva la base estable. Todas las ramas comienzan desde la misma versión inicial; se actualizan con `main` antes de trabajar en ellas.

## Próximas entregas

1. Detallar hero y navegación: jerarquía, espaciado, estados de interacción y adaptación móvil.
2. Presentar Portal Docente con capturas originales, sin rediseñar su interfaz.
3. Completar Casa Artesanal con contenido y materiales reales.
4. Desarrollar sobre mí y los cuatro proyectos secundarios.
5. Añadir contacto y enlaces profesionales confirmados.

No incluir Dashboard de energía. No inventar resultados, métricas ni capacidades de los proyectos.

Subir código a este repositorio no publica automáticamente cambios en Sites. La publicación se realiza por separado después de revisar cada entrega.
