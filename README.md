# APP UNLIMITED

Aplicación móvil multiplataforma (iOS y Android) moderna y escalable.

## Stack Tecnológico

- **Framework:** React Native (Expo SDK 52)
- **Lenguaje:** TypeScript
- **Navegación:** Expo Router (file-based routing)
- **Estilos:** StyleSheet nativo de React Native
- **Iconos:** Ionicons (@expo/vector-icons)

## Estructura del Proyecto

```
/app
  ├── _layout.tsx          # Configuración global de navegación
  ├── index.tsx            # Pantalla de Bienvenida/Landing
  └── (auth)               # Grupo de rutas de autenticación
        ├── _layout.tsx    # Layout del grupo auth
        ├── login.tsx      # Pantalla de Login
        └── register.tsx   # Pantalla de Registro
```

## Instalación

1. Instalar dependencias:
```bash
npm install
```

2. Agregar assets requeridos en la carpeta `/assets`:
   - `icon.png` (1024x1024)
   - `splash-icon.png` (512x512)
   - `adaptive-icon.png` (1024x1024)
   - `favicon.png` (48x48)

3. Iniciar el proyecto:
```bash
npm start
```

## Comandos Disponibles

- `npm start` - Inicia Expo en modo desarrollo
- `npm run android` - Inicia en Android
- `npm run ios` - Inicia en iOS
- `npm run web` - Inicia en navegador web

## Características del Módulo de Autenticación

### Pantalla de Login
- Logo/Título de la app centrado
- Campo de Email con validación de formato
- Campo de Contraseña con botón mostrar/ocultar
- Botón "Iniciar Sesión" (imprime datos en consola)
- Enlace a pantalla de Registro

### Pantalla de Registro
- Campo de Nombre
- Campo de Email con validación
- Campo de Contraseña con botón mostrar/ocultar
- Botón "Crear Cuenta" (imprime datos en consola)
- Enlace a pantalla de Login
