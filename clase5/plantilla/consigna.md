# Ejercicio - Formulario de contacto

Objetivo: Completar el formulario de contacto para que solicite los datos correspondientes y los envíe mediante formsubmit.co.

1. Abrir los archivos `index.html` y `css/estilos.css`
2. Completar el formulario dentro de `<form>` con los campos solicitados
3. Configurar el envío del formulario usando formsubmit.co
4. Crear una página `gracias.html` a la que se redirija al usuario luego de enviar el formulario

## Especificaciones

### Datos a solicitar

- Nombre
- Apellido
- Email
- Mensaje

### Estructura y layout

- Nombre y Apellido se muestran en dos columnas, uno al lado del otro
- Al pie del formulario, un checkbox para aceptar los términos y condiciones junto al botón de enviar

### Envío del formulario (formsubmit.co)

- `method="post"`
- `action="https://formsubmit.co/<tu-email>"` (reemplazar por un email propio o alias de formsubmit)
- Agregar asunto personalizado
- Template: box
- Redirección: URL de `gracias.html` (poner url del sitio en Netlify)

### Página de agradecimiento (`gracias.html`)

- Mismo encabezado que `index.html`
- Un link para volver a `index.html`

## Referencia visual

Ver `muestra.png` (formulario) y `muestra-gracias.png` (página de agradecimiento).
