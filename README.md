# 🥖 Panadería Potros - Sistema POS y Gestión E-Commerce

Desarrollo Frontend del sistema integral de administración y punto de venta para "Panadería Potros". Construido con **React** y **Vite**, este sistema está diseñado para manejar el ciclo completo del negocio: desde el control de inventarios hasta el corte de caja y reportes analíticos.

### 🧑‍💻 Mi Rol y Aportaciones (Commits por @alancho21)
Como desarrollador principal del cliente web, lideré la creación e integración de los siguientes módulos:
- **Módulo de Ventas (POS):** Carrito de compras interactivo con validación de stock en tiempo real, cálculo de totales y generación automática de tickets de impresión HTML.
- **Módulo de Reportes Analíticos:** Dashboard interactivo que filtra datos por fechas, vendedores y productos. Implementación de funciones puras en JavaScript para exportar reportes directamente a CSV y PDF.
- **Gestión de Usuarios y Roles:** Vistas protegidas (`RequireAuth`) para roles de Administrador, Vendedor y Cliente, con un panel completo de CRUD y asignación de permisos.
- **Consumo de APIs Híbridas:** Configuración de instancias de Axios e interceptores (Bearer Tokens) para consumir simultáneamente un backend en Node.js/MongoDB y un catálogo de productos en PHP/Laravel.

### 🛠️ Tecnologías Utilizadas
- **Core:** React 19, React Router DOM v7, Vite.
- **Estilos:** Tailwind CSS (Custom themes, degradados y utilidades de opacidad), CSS Modules.
- **Peticiones HTTP:** Axios (con interceptores personalizados).
- **Notificaciones:** React Toastify.

### 📱 Prototipo Móvil (React Native)
Intentamos expandir el sistema a una aplicación móvil multiplataforma usando tecnologías web. El repositorio con el código fuente del cliente móvil (actualmente archivado y no funcional) puede consultarse aquí para revisión arquitectónica:
👉 **[Ver Prototipo Móvil (React Native)]((https://github.com/alancho21/ProyectoSoaMovil))
