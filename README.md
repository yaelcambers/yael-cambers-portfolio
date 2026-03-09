# Yael Replica Next

Replica visual del sitio de referencia en Framer, construida con Next.js y React.

## Stack

- Next.js 15
- React 19
- TypeScript
- Framer Motion
- CSS global con fuente: `"Helvetica Neue", Helvetica, Arial, sans-serif`

## Correr local

```bash
npm install
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000)

## Build producción

```bash
npm run build
npm run start
```

## Deploy en Vercel

1. Sube esta carpeta como proyecto Git.
2. En Vercel crea un proyecto nuevo.
3. Framework: `Next.js` (auto-detectado).
4. Build command: `npm run build`.
5. Output: automático de Next.

## Deploy en Netlify

1. Crea sitio nuevo desde Git.
2. Build command: `npm run build`.
3. Publish directory: `.next`.
4. Usa el plugin oficial de Netlify para Next.js (`@netlify/plugin-nextjs`) o Build Image que lo detecte automáticamente.

## Metadata incluida

- `<title>Yael Cambers</title>`
- Open Graph y Twitter Card con imagen principal de hero
- Favicon `C` en estilo Helvetica (archivo `app/icon.svg`)
