# Don Pisorno - Sistema de Gestión

Aplicación web moderna para la gestión integral de pedidos, producción, costos, inventario y ganancias.

## Tecnologías

- **Frontend**: React + TypeScript + Vite
- **Backend**: Supabase
- **Base de datos**: PostgreSQL (Supabase)
- **UI**: TailwindCSS + Framer Motion
- **Gráficos**: Recharts

## Configuración

1. Crear proyecto en Supabase
2. Ejecutar el archivo `sql/schema.sql` en el SQL Editor de Supabase
3. Configurar las variables de entorno en `.env`:

```bash
cp .env.example .env
```

Editar `.env` con las credenciales de Supabase:
- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`

4. Instalar dependencias:
```bash
npm install
```

5. Ejecutar en desarrollo:
```bash
npm run dev
```

## Módulos

- **Dashboard**: Estadísticas en tiempo real de pedidos, ventas y ganancias
- **Pedidos**: Gestión completa con estados y notificaciones
- **Inventario**: Control de stock con alertas
- **Gastos**: Registro de gastos por categoría
- **Reportes**: Gráficos interactivos de ventas y ganancias
- **Aderezos**: Gestión de precios y stock

## Roles de Usuario

- **Administrador**: Acceso total
- **Operador**: Gestión de pedidos y producción
- **Repartidor**: Gestión de entregas