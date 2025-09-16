# PruebaFrontend
Listado y detalle de usuarios desde API pública


Prueba Técnica Frontend: Listado y Detalle de Usuarios

Este es un proyecto de demostración que cumple con los requerimientos de una prueba técnica de desarrollo frontend. La aplicación consume una API pública (`JSONPlaceholder`) para listar usuarios en una tabla y, al hacer clic en uno, muestra todos sus detalles en una vista dedicada.

Tecnologías

- React: Framework de UI para crear la interfaz de usuario.
- Vite: Bundler y entorno de desarrollo que optimiza la velocidad del proyecto.
- TypeScript: Añade tipado estático para un desarrollo más robusto y con menos errores.
- React Query: Para gestionar el estado de los datos remotos (loading, error, caching) de forma eficiente y declarativa.
- React Router DOM: Para la navegación entre la lista y la página de detalle.
- Tailwind CSS: Framework de CSS utilitario que permite un diseño rápido, responsivo y "mobile-first".
- Vitest & React Testing Library: Para escribir tests unitarios y de integración que aseguran la calidad y funcionalidad del código.


Instalación y Uso

Asegúrate de tener Node.js (v18+) instalado.

1.  Clona el repositorio:
    bash
    git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
    cd nombre-del-repo
    

2.  Instala las dependencias del proyecto:
    bash
    npm install
    

3.  Inicia la aplicación en modo de desarrollo:
    bash
    npm run dev
    
    La aplicación se abrirá en `http://localhost:5173`.

Ejecutar Tests

Para ejecutar las pruebas de la aplicación, usa el siguiente comando:
bash
npm run test


Criterios de Cumplimiento y Decisiones de Diseño

Aquí es donde demuestras que cumpliste con los requerimientos de la prueba.-----------------------------------------------------------------


## ✅ Cumplimiento de Requisitos

- Listado y Detalle: La aplicación muestra una tabla de usuarios con filtros y una vista de detalle completa.
- Estado de Carga y Error: Se muestran mensajes claros durante la carga de datos y en caso de errores.
- Búsqueda y Filtro: La funcionalidad de búsqueda por nombre y filtro por ciudad funciona correctamente en el cliente.
- Diseño Responsive y Accesibilidad: El diseño es adaptable a diferentes tamaños de pantalla (mobile-first) y permite la navegación por teclado.
- Estructura y Mantenimiento: El proyecto sigue una estructura modular (`componentes`, `paginas`, `servicios`, `hooks`) para facilitar su mantenimiento.
