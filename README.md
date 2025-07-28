# 🚀 Pruebas E2E - API de Gestión de Clientes

Este repositorio contiene pruebas End-to-End (E2E) automatizadas para validar la API de gestión de clientes, incluyendo autenticación, CRUD completo y validaciones de negocio.

## 📦 Requisitos

- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [npm](https://www.npmjs.com/) (incluido con Node.js)

## 🔧 Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/e2e-tests-backend.git
   cd e2e-tests-backend

2. Instala las dependencias

    ```bash
    npm install

    Este comando instala:

    - newman: ejecutor de colecciones Postman
    - newman-reporter-htmlextra: generador de reportes visuales

3. Ejecución básica (consola + reporte HTML)

    ```bash
    npm test

    Este comando:

    - Ejecuta la colección completa.
    - Genera un informe detallado en report.html.

4. Abre el informe con tu navegador:

    ```bash
    open report.html
