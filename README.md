# Proyecto Final: Plataforma Multi-Tenant para Sistema de Asistencia

Este proyecto implementa una plataforma SaaS para crear y administrar tenants (instituciones educativas) de un sistema de registro de asistencia, cumpliendo con los requisitos de aislamiento, despliegue automático y monitoreo.

## 🏗️ Arquitectura y Herramientas
- **Frontend:** Vanilla JavaScript (app-asistencia/frontend).
- **Backend App:** Node.js + Express + SQLite (app-asistencia/backend).
- **Plataforma de Gestión:** Node.js + Express (plataforma/).
- **Infraestructura:** OpenTofu (infraestructura/).
- **Configuración:** cloud-init (para instalar la app en AWS).
- **Monitoreo:** Grafana (instalado en cada tenant).

## 🚀 Guía de Uso Rápido
### 1. Levantar la Plataforma de Gestión
```bash
cd plataforma
npm install
npm start
