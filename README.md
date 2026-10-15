# Nexo U Mockup

Mockup funcional de una plataforma de aprendizaje entre pares para estudiantes de la Universidad Católica Boliviana, sede La Paz. La interfaz toma como referencia la organización de LinkedIn y aplica identidad visual institucional de la UCB.

## Funcionalidades

- Catálogo con búsqueda y filtros por modalidad y categoría.
- Inicio de sesión demostrativo al intentar inscribirse.
- Inscripción local y actualización inmediata de la agenda.
- Calendario de cursos elegidos.
- Perfil con carrera, intereses, reputación, puntos y cursos impartidos.
- Analíticas personales de aprendizaje y contribución.
- Diseño adaptable y navegación accesible.

## Tecnologías

- Vue 3 con Composition API.
- Vite.
- Vue Router.
- Pinia.
- Lucide Vue.
- CSS sin framework visual.

## Ejecución

```bash
npm install
npm run dev
```

Abrir la dirección indicada por Vite, normalmente `http://localhost:5173`.

## Compilación

```bash
npm run build
```

## Acceso demostrativo

El correo aparece precargado y cualquier contraseña permite continuar. No existe autenticación real ni se envían credenciales.

## Integración futura

Los datos de prueba se encuentran en `src/data/mockData.js`. El estado demostrativo está en `src/stores/app.js` y el cliente HTTP base en `src/services/api.js`. Consulta `docs/integracion-api.md` para los contratos propuestos.

## Alcance

Este proyecto es un mockup de Frontend. No implementa autenticación, persistencia, cálculos analíticos del servidor ni base de datos.
