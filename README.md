# 🏨 Sistema de Gestión de Hostal (SGH)

Este proyecto corresponde al desarrollo de un Sistema de Gestión de Hostal (SGH) para el hostal "Doña María Gracia", diseñado para optimizar y centralizar la administración de operaciones. La plataforma es una aplicación web que facilita la gestión de reservas, habitaciones, servicios de comedor, proveedores, y facturación, con el objetivo de mejorar la eficiencia operativa y apoyar la toma de decisiones mediante análisis e informes.

## ✨ Funcionalidades Principales

- 👥 **Gestión de Clientes**: Creación de perfiles de clientes, tanto individuales como corporativos, para un seguimiento detallado.
- 🛏️ **Administración de Habitaciones y Reservas**: Control del estado, disponibilidad y asignación de habitaciones.
- 🍽️ **Servicios de Comedor**: Registro y gestión de platos, precios y minutas semanales.
- 📦 **Control de Proveedores**: Administración de datos de contacto y términos de contratos.
- 💸 **Facturación y Órdenes de Compra**: Generación y gestión de facturas y pedidos a proveedores, con opciones de filtrado y búsqueda.
- 📊 **Informes y Análisis**: Creación de informes personalizados en formatos PDF y Excel sobre ocupación de habitaciones, servicios y desempeño de proveedores.

## 🔧 Características Adicionales

- 📱 **Interfaz Adaptativa**: Compatibilidad con dispositivos móviles.
- 🔒 **Seguridad**: Registro de actividades mediante logs y gestión de acceso mediante roles de usuario.
- 📈 **Escalabilidad y Mantenibilidad**: Capacidad de crecimiento para adaptarse a nuevas demandas y actualizaciones.

## 👤 Perfiles de Usuario

- 🧑‍💼 **Administrador**: Acceso completo al sistema, con capacidad de generar informes y gestionar usuarios.
- 🧑‍✈️ **Recepcionista**: Responsable de reservas, check-in/check-out, y coordinación de servicios.
- 👥 **Cliente y Proveedor**: Acceso a información de reservas y pedidos, respectivamente, facilitando una experiencia de autogestión.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
