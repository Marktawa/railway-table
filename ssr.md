| Framework | Build Command | Start Command |
| --- | --- | --- |
| Analog | ng build | node dist/analog/server/index.mjs |
| Astro | astro build | node ./dist/server/entry.mjs |
| Next.js | next build | next start |
| Nuxt | nuxt build | node .output/server/index.mjs |
| Remix | npx remix vite:build | npx remix-serve build/server/index.js |
| Gatsby | npx gatsby build | npx gatsby serve |
| Solid | vite build | npx http-server ./dist |
| Qwik | qwik build | node server/entry.express |
| SvelteKit | vite build | cp package.json build/ && cp package-lock.json build/ && cd build && npm ci --omit dev && node build |
