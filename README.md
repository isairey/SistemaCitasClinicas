# 🏥 Sistema de Gestión de Citas para Clínicas

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Activo-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Versión-1.0-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Licencia-Educativa-orange?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CodeIgniter-3.1.10-EE4623?style=for-the-badge&logo=codeigniter&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-3.3.7-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/jQuery-2.2.4-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/jQuery_UI-1.12.1-FFCA28?style=for-the-badge&logo=jqueryui&logoColor=black">
  <img src="https://img.shields.io/badge/FullCalendar-JS-3788D8?style=for-the-badge">
</p>

---

## 🏥 Descripción

Sistema de gestión de citas para clínicas desarrollado con tecnologías modernas para facilitar la administración de pacientes, doctores y consultas médicas.  
Permite gestionar citas, historiales y procesos administrativos desde una sola plataforma.

---

## 🚀 Funcionalidad Actual

### 🏢 Aplicación de Back Office

#### 📅 Módulo de Citas
Operaciones CRUD para citas y búsqueda mediante filtros:
- Fecha
- Hora de visita
- Número MR (historial médico)

---

#### 👨‍⚕️ Módulo de Doctores
- CRUD de doctores  
- Búsqueda por:
  - Nombre  
  - Especialización  
  - Teléfono  

##### 🩺 Especialización de Doctores
Submódulo para gestionar especialidades médicas.

---

#### 🧑‍🦽 Módulo de Pacientes
- CRUD de pacientes  
- Búsqueda por:
  - Teléfono  
  - Nombre del padre  
  - Número MR  

---

#### 🗓️ Módulo de Horarios
- Configuración de horarios semanales de doctores  

---

#### 💊 Módulo de Prescripciones
- Recetas médicas  
- Descarga en PDF  

---

#### ⚙️ Módulo de Administradores
- Gestión de usuarios del sistema  

---

#### 📊 Dashboard
- Búsqueda de citas por fecha  
- Filtros por hora y doctor  

---

### 🏥 Aplicación Front Office

- Registro de pacientes nuevos y recurrentes  
- Agendamiento de citas  
- Selección de doctor y horario  

---

## ⚙️ Instalación

```bash
git clone https://github.com/isairey/SistemaCitas.git
cd appointment-management-system
composer install
