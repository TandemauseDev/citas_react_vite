# React + Vite

# Veterinary Appointment Management System

## Descripción del Proyecto

Este proyecto es una aplicación web para gestionar citas veterinarias, construida con React, Vite y Tailwind CSS. La aplicación permite a los usuarios agregar información sobre mascotas, como nombre, propietario, fecha de alta y síntomas. La interfaz se divide en dos secciones principales: el formulario a la izquierda para agregar o editar citas y la lista de pacientes a la derecha.

### Funcionalidades Principales

1. **Agregar Paciente:**
   - El formulario a la izquierda solicita información relevante, como nombre de la mascota, correo, nombre del propietario, fecha de alta y síntomas.
   - Los datos se validan antes de ser agregados a la lista.

2. **Lista de Pacientes:**
   - La lista de pacientes se muestra a la derecha y se actualiza dinámicamente a medida que se agregan o editan citas.
   - Si no hay pacientes, se muestra un mensaje informativo.

3. **Editar y Eliminar:**
   - Se proporciona la capacidad de editar y eliminar citas existentes.
   - Al editar, los campos del formulario se llenan automáticamente con los datos del paciente seleccionado.

4. **Local Storage:**
   - Los datos de los pacientes se almacenan localmente, lo que garantiza que la información persista incluso después de recargar la página.

5. **Interfaz Dinámica:**
   - La interfaz se adapta según las acciones realizadas. Por ejemplo, el texto cambia según si hay o no pacientes en la lista.
   - El botón de agregar en el formulario también se adapta cuando se está editando un paciente.

### Tecnologías Utilizadas

- **React:** Biblioteca de JavaScript para construir interfaces de usuario interactivas.
- **Vite:** Herramienta de desarrollo para proyectos de JavaScript y TypeScript.
- **Tailwind CSS:** Framework de diseño de utilidades CSS para estilizar la aplicación de manera eficiente.

## Instrucciones de Ejecución

1. **Instalación de Dependencias:**
   ```bash
   npm install

## preview 
-  The application is available at [netlify](https://6568283d158c8769d0a6c389--cozy-liger-8bd0ee.netlify.app).



- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# citas_react_vite
