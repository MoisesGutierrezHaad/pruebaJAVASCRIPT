## Configuración del entorno

Instalar dependencias:

```bash
npm install
```

Ejecutar proyecto:

```bash
npm run dev
```

Este comando levanta simultáneamente:

- Vite
- JSON Server

gracias al uso de Concurrently.

---

## Scripts sugeridos

json
{
  "scripts": {
    "client": "vite",
    "server": "json-server --watch db.json --port 3000",
    "dev": "concurrently \"npm run client\" \"npm run server\""
  }
}

## Credenciales de prueba

Administrador:

txt
admin@test.com
123456

Usuario:

txt
user@test.com
123456


## Funcionalidades base incluidas

- Login funcional
- Consumo de API mediante JSON Server
- Persistencia de sesión con LocalStorage
- Logout
- Router SPA
- Protección básica de rutas
- Sidebar reutilizable
- Página 404 personalizada
- Configuración de TailwindCSS
- Configuración de Vite


## Módulos pendientes para desarrollar

Los coders deberán implementar:

- CRUD de reservas
- CRUD de espacios
- Gestión de roles
- Guards avanzados
- Validaciones de permisos
- Dashboard administrativo
- Estadísticas
- Filtros y búsquedas
- Notificaciones
- Reglas de negocio



