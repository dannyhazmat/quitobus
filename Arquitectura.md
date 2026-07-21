# Arquitectura del Sistema - Quitobus

## Stack Tecnológico
- **Frontend:** Flutter
- **Backend / Base de datos:** Supabase (PostgreSQL, Auth, Realtime)
- **Mapas:** MapTiler
- **Control de versiones:** GitHub

## Módulos
- driver_app
- passenger_app
- coop_admin
- master_admin

## Base de datos (Tablas)
- conductores
- cooperativas
- buses
- rutas
- vueltas
- gps
- usuarios
- alertas

## Flujo Conductor (MVP)
QR → Validación → Inicio Jornada → GPS → Registro de vuelta → Fin Jornada
