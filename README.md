# App de Localización de Eventos locales

La idea sería que los usuarios puedan encontrar y agregar eventos (conciertos, mercados, actividades al aire libre, etc.) cerca de su ubicación actual o en otras ciudades. Aquí tienes un desglose de lo que podrían incluir y cómo estructurar el proyecto:

## Funcionalidades clave

1. **Inicio de sesión/Registro**: Usar Supabase para la autenticación. Los usuarios pueden registrarse e iniciar sesión con email y contraseña y/o redes sociales.
2. **Geolocalización y Mapas**: Integrar mapas (Google Maps o Apple Maps) para mostrar eventos cercanos y permitir a los usuarios crear nuevos eventos seleccionando ubicaciones en el mapa.
3. **Base de datos de eventos**: Usar Supabase como backend para almacenar la información de los eventos (nombre, descripción, fecha, hora, ubicación, organizador, etc.).
4. **Filtrado y búsqueda**: Los usuarios podrán buscar eventos por categoría (música, deportes, comida, etc.) y filtrar eventos por proximidad o fecha.
5. **Favoritos**: Los usuarios pueden guardar eventos como favoritos para consultarlos más tarde.
6. **Comentarios/Reseñas**: Agregar la opción de que los usuarios comenten o dejen reseñas de los eventos a los que asistieron.

## Plan de desarrollo de 11 semanas

1. **Semana 1**: Introducción al proyecto, setup de React Native y Supabase, creación del proyecto básico.
2. **Semana 2**: Configuración de autenticación con Supabase (registro, inicio de sesión, cierre de sesión).
3. **Semana 3**: Introducción a la geolocalización en React Native. Mostrar la ubicación actual en el mapa.
4. **Semana 4**: Configuración de Supabase como base de datos. Crear un CRUD básico para eventos.
5. **Semana 5**: Integrar mapas, permitiendo a los usuarios seleccionar ubicaciones para los eventos.
6. **Semana 6**: Mostrar eventos en el mapa y lista de eventos cercanos.
7. **Semana 7**: Implementar el filtrado y búsqueda de eventos por categorías y proximidad.
8. **Semana 8**: Añadir funcionalidad de favoritos y permitir que los usuarios guarden eventos.
9. **Semana 9**: Añadir la funcionalidad de comentarios/reseñas en los eventos.
10. **Semana 10**: Testing y ajustes finales. Presentación del proyecto final.

Esta estructura permite que los estudiantes aprendan a manejar autenticación, bases de datos y mapas aplicando tecnologías que se usan en aplicaciones del mundo real.
