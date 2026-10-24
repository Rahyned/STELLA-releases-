# STELLA

**Sistema de gestión para el laboratorio dental RioDent: trabajos, cuentas corrientes y reportes en una app de escritorio.**

Este repositorio publica solo el instalador. El código fuente es privado.

## Qué resuelve

El laboratorio llevaba los trabajos en papel, sin seguimiento ni cuentas corrientes. STELLA ordena cada trabajo de principio a fin y el laboratorio la usa todos los días.

## Funcionalidades principales

- Trabajos con estados y seguimiento.
- Cuentas corrientes de clientes.
- Usuarios con roles e inicio de sesión.
- Reportes y comprobantes en PDF.
- Backup automático al iniciar y respaldo en Google Drive.
- Actualizaciones automáticas desde la propia app.

## Stack

Python · PyQt5 · FastAPI · SQLModel · JWT · ReportLab.

## Instalación

1. Descargá [STELLA_Setup.exe](https://raw.githubusercontent.com/Rahyned/STELLA-releases-/main/STELLA_Setup.exe).
2. Ejecutalo y seguí el asistente (requiere permisos de administrador).
3. Al terminar, STELLA se abre sola. Iniciá sesión con tu usuario.

> Si Windows muestra el aviso de SmartScreen, elegí **"Más información" → "Ejecutar de todas formas"**.

## Actualizaciones y datos

- STELLA busca actualizaciones al iniciar y desde **Configuración → Actualizaciones**. La versión nueva se instala con un clic.
- Los datos y la configuración se guardan en `%APPDATA%\STELLA\`. Instalar o actualizar no los borra ni los modifica.

## Estado

En uso diario en Laboratorio RioDent desde enero de 2026.

## Autor

© 2026 Lautaro Rodríguez. Todos los derechos reservados. · [GitHub](https://github.com/Rahyned)
