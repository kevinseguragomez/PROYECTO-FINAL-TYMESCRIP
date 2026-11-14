# PhotoVault

**Estudiante:** KEVÍN DARWIN SEGURA GÓMEZ

## Descripción
Aplicación móvil desarrollada con React Native, Expo y TypeScript. Permite a un
usuario iniciar sesión con correo y contraseña (Supabase Auth) y, una vez
autenticado, seleccionar una fotografía de la galería o capturarla con la cámara,
visualizarla, cambiarla por otra o eliminarla de la vista previa. La sesión se
mantiene al cerrar y reabrir la app y se puede cerrar sesión desde la pantalla
principal.

## Instalación y ejecución
1. Clonar el repositorio:
   git clone https://github.com/TU_USUARIO/photovault.git
   cd photovault
2. Instalar dependencias:
   npm install
3. Crear el archivo `.env` a partir de `.env.example` y completar:
   EXPO_PUBLIC_SUPABASE_URL=...
   EXPO_PUBLIC_SUPABASE_ANON_KEY=...
4. Crear un usuario en Supabase (Authentication → Users → Add user).
5. Ejecutar:
   npx expo start
6. Escanear el QR con Expo Go.

## Dependencias principales
- expo
- react-native
- typescript
- @supabase/supabase-js
- @react-native-async-storage/async-storage
- react-native-url-polyfill
- expo-image-picker
- expo-linear-gradient

## Estructura
- `src/screens`: LoginScreen, HomeScreen
- `src/services`: supabase, auth, photos
- `src/components`: GradientButton
- `src/theme`: colores y estilos

## Capturas
![Login](screenshots/01-login.png)
![Home](screenshots/02-home.png)
![Galería](screenshots/03-galeria.png)
![Cámara](screenshots/04-camara.png)
