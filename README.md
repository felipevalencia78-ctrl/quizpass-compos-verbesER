# Quiz passé composé ER — texte à trous

Estructura solicitada:

1. Primera pantalla: pide el prénom de l'étudiant(e).
2. Segunda pantalla:
   - saludo con el nombre del estudiante,
   - petit rappel,
   - instrucción simple,
   - caja de participios pasados,
   - 15 frases para completar.

## Probar en Cursor

```bash
npm install
npm run dev
```

## Subir a Vercel

- Framework Preset: Vite
- Build Command: npm run build
- Output Directory: dist

## Editar las preguntas

En `index.html`, busca:

```js
const sentences = [
```

El espacio vacío se marca con `___`.
