# Práctica de trabajo por apartados

El objetivo es practicar un encargo web: entender el requisito, implementar un cambio pequeño, comprobarlo y presentar una entrega revisable.

## Flujo de una entrega

1. Define el objetivo y cómo sabremos que está terminado. Ejemplo: «Mejorar la jerarquía del hero, sin desbordamiento horizontal en móvil y con un enlace claro a proyectos».
2. Actualiza `main` y entra a la rama del apartado:

   ```bash
   git switch main
   git pull --ff-only origin main
   git switch feature/hero
   git merge main
   ```

   Si ya tienes cambios sin guardar, haz un commit antes de cambiar de rama. Si hay conflictos, resuélvelos y revisa el resultado antes de continuar.

3. Edita los archivos necesarios. Aunque existen ramas por sección, el HTML y CSS son compartidos: trabaja un apartado a la vez para reducir conflictos.
4. Revisa en navegador a tamaño móvil y escritorio. Comprueba navegación por teclado, foco visible, legibilidad y enlaces. No debe aparecer desplazamiento horizontal inesperado.
5. Revisa y guarda los archivos concretos:

   ```bash
   git diff
   git add dist/index.html dist/style.css
   git commit -m "Mejora la jerarquía y el espaciado del hero"
   git push -u origin feature/hero
   ```

6. Abre un pull request hacia `main`: explica el requisito, qué cambió y cómo lo comprobaste. Incluye capturas cuando ayuden a revisar el diseño.
7. Revisa el diff y corrige lo necesario antes de unirlo. Después actualiza `main` localmente.

No abras un pull request vacío: las ramas están preparadas, pero necesitan cambios antes de proponer una entrega.

## Primera práctica: hero

- Mantener el enfoque Front End + diseño de interfaces y el idioma español.
- Dar más detalle visual sin perder aire entre elementos.
- Respetar negro, violeta y la selección tipográfica.
- Revisar el título, el texto de apoyo y el enlace a proyectos en móvil y escritorio.
- No añadir datos personales o profesionales que no estén confirmados.
