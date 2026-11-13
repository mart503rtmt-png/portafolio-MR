# Próxima entrega: detalle de proyectos y contacto

Requisitos solicitados por Marcos Reyes.

## 1. Detalle de cada proyecto

Al pulsar un proyecto principal o secundario, abrir una ventana modal sin abandonar la página.

Contenido por proyecto:
- Problema y contexto.
- Mi responsabilidad y aportes concretos.
- Decisiones de diseño o implementación y por qué las tomé.
- Tecnologías utilizadas.
- Evidencia: capturas originales, demo, repositorio o resultados confirmados.

Tono: primera persona, directo y seguro. Mostrar capacidad mediante decisiones y evidencia. No afirmar superioridad sobre otros ni inventar resultados, responsabilidades o tecnologías.

Portal Docente conserva su interfaz real: no rediseñar sus capturas.

Criterios de aceptación:
- Cada proyecto abre su propio contenido mediante clic o teclado.
- La ventana tiene título accesible y botón visible para cerrar.
- Se puede cerrar con Escape; al cerrar, el foco vuelve al proyecto de origen.
- El foco permanece dentro mientras está abierta y el fondo no se desplaza.
- El contenido largo se puede recorrer en móvil sin desbordamiento horizontal.

Ramas previstas: `feature/proyectos` para los casos principales y el componente modal; `feature/exploraciones` para los casos secundarios, después de integrar el componente.

Pendiente: Marcos debe confirmar problema, participación, tecnologías y evidencias de cada proyecto. Empezar con Portal Docente y Casa Artesanal.

## 2. Contacto directo

Añadir una sección visible de contacto y un acceso desde la navegación. El tono propuesto es «¿Tienes un proyecto en mente? Hablemos».

Ofrecer correo y/o WhatsApp según la preferencia de Marcos. Para correo mediante `mailto:`, indicar que abre la aplicación de correo y preparar un asunto editable. No mostrar confirmación de envío porque la página no envía el mensaje. Para WhatsApp, usar el número confirmado en formato internacional.

Criterios de aceptación:
- El destino pertenece a Marcos y está confirmado expresamente para contacto público.
- Un clic inicia la conversación por el canal elegido.
- El correo visible se puede copiar; si falla la copia, permanece seleccionable.
- Los enlaces funcionan con teclado y tienen foco visible.
- No añadir un formulario que aparente enviar mensajes sin un servicio de envío configurado.

Rama prevista: `feature/contacto`. El acceso desde navegación se integra con el mismo cambio para que no apunte a una sección inexistente.

Confirmado: solo WhatsApp Business, +503 7470 2108. Se implementa un enlace directo con mensaje editable; no se añade correo.

## Secuencia de práctica

1. Confirmar los datos pendientes.
2. Desarrollar una mejora en su rama.
3. Revisar comportamiento en móvil, escritorio y teclado.
4. Crear un commit y subir la rama.
5. Abrir un pull request con requisito, implementación y comprobaciones.
6. Revisar, integrar en `main` y publicar la entrega revisada.

Repositorio creado por el usuario: `mart503rtmt-png/portafolio-MR`. El trabajo se organiza por ramas y pull requests.
