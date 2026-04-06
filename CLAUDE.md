# Proyecto 29 — AenaJones

> Interactive video experience with React + TypeScript + Vite

## Contexto
AenaJones es una aplicación web interactiva que combina video, narrativa ramificada y decisiones del usuario. Presenta un flujo de historias con puntos de decisión, pantalla de splash inicial, autenticación por contraseña y pantalla final.

## Arquitectura
- **Stack**: React 19 + TypeScript + Vite
- **Estructura de componentes**:
  - `App.tsx` — Componente raíz
  - `components/VideoWall.tsx` — Reproducción de videos
  - `components/StoryFlow.tsx` — Lógica de flujo narrativo
  - `components/DecisionOverlay.tsx` — Overlay con opciones de decisión
  - `components/PasswordGate.tsx` — Puerta de autenticación
  - `components/AenaSplash.tsx` — Pantalla de bienvenida
  - `components/EndScreen.tsx` — Pantalla final
  - `components/ProgressBar.tsx` — Barra de progreso
  - `types.ts` — Definiciones TypeScript
- **Build**: Vite con HMR en desarrollo
- **Linting**: ESLint configurado

## Notas para IAs
- La aplicación es un juego/experiencia interactiva con estados y decisiones del usuario
- Los componentes principales gestionan flujos de video y narrativa
- Requiere contenido multimedia (videos) para funcionar
- TypeScript types en `types.ts` define la estructura de datos de la narrativa
- Para cambios importantes: considerar el flujo de estado y decisiones del usuario
- El build se ejecuta con `npm run build` (tsc + vite build)
