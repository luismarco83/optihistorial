# OptiHistorial (Expo)

App offline-first para historiales clínicos de ópticas.

## Cómo obtener el APK (desde el teléfono o cualquier dispositivo)

### 1. Crear cuenta en Expo (gratis)
- Entra a: https://expo.dev
- Crea una cuenta

### 2. Subir el proyecto
Opciones fáciles:
- Sube esta carpeta a **GitHub** (desde el teléfono con la app de GitHub o un navegador)
- O usa **Snack Expo** (https://snack.expo.dev) pegando los archivos

### 3. Generar el APK con EAS (en la nube)

Desde una terminal (puedes usar un servicio online como [replit](https://replit.com) o pedirle a alguien):

```bash
npm install -g eas-cli
npx eas login
npx eas build:configure
npx eas build -p android --profile preview
```

Al terminar, Expo te dará un **link para descargar el APK** directamente en tu teléfono.

### Alternativa más simple (recomendada si no tienes PC)

1. Crea cuenta en https://expo.dev
2. Instala la app **Expo Go** en tu teléfono
3. Sube el código a GitHub
4. En expo.dev conecta el repositorio y lanza un **Build** → perfil `preview` (APK)
5. Descarga e instala el APK

## Funciones incluidas (Etapa 1)

- Pacientes (crear, buscar, editar)
- Consultas con graduación OD / OI
- Ventas de lentes
- Historial del paciente
- 100% offline
- Exportar respaldo local

## Color principal
`#0A4D8C`
