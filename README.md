# 🎰 RuletaSorteos.es

**Ruleta de Sorteos Online Gratuita** - La herramienta definitiva para realizar sorteos aleatorios de forma visual, divertida y 100% transparente.

[![Astro](https://img.shields.io/badge/Astro-5.16-ff5d01?logo=astro)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1-38bdf8?logo=tailwindcss)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178c6?logo=typescript)](https://typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🌐 Demo

**[https://ruletasorteos.es](https://ruletasorteos.es)**

## ✨ Características

### 🎡 Ruleta Clásica
- Ruleta circular animada estilo "rueda de la fortuna"
- **6 modos de juego**: Ganador, Eliminación, Equipos, Orden aleatorio, Troll y Misterio
- Personalización total: colores, velocidad (1s/5s/10s), sonidos, confeti
- Importación de participantes (TXT, CSV, JSON)
- Hasta 500 participantes
- 🎄 Modo Navidad con nieve

### 🎰 Ruleta Casino
- Estilo horizontal tipo casino europeo
- Casillas rojo/negro + verde opcional (2.7% probabilidad real)
- Modo Muerte Súbita (eliminación progresiva)
- Modos Troll y Misterio combinables

### 🐦 Ruleta Twitter (Próximamente)
- Integración con Twitter/X para sorteos de seguidores

### ⚖️ Sistema Provably Fair
- Verificador de semillas integrado
- Algoritmo determinista y transparente
- `crypto.getRandomValues()` para aleatoriedad criptográfica
- Sin servidor: todo se ejecuta localmente en el navegador

## 🔒 Seguridad

- **100% Local**: Los datos nunca salen de tu navegador
- **Sin cookies ni tracking**
- **CSP estricta** configurada
- **Sanitización XSS** en todas las entradas
- **Headers de seguridad**: X-Frame-Options, X-Content-Type-Options, Referrer-Policy

## 🚀 Tecnologías

- **Framework**: [Astro 5](https://astro.build) (Static Site Generation)
- **Estilos**: [Tailwind CSS 4](https://tailwindcss.com)
- **Lenguaje**: TypeScript
- **Gráficos**: Canvas API
- **Audio**: Web Audio API
- **SEO**: Schema.org, Open Graph, Twitter Cards

## 📦 Instalación

```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/ruletasorteos-es.git
cd ruletasorteos-es

# Instalar dependencias
npm install

# Desarrollo
npm run dev

# Producción
npm run build
npm run preview
```

## 📁 Estructura

```
├── src/
│   ├── components/
│   │   ├── Roulette.astro       # Ruleta clásica circular
│   │   ├── CasinoRoulette.astro # Ruleta casino horizontal
│   │   └── TwitterRoulette.astro # Ruleta Twitter (próximamente)
│   ├── layouts/
│   │   └── Layout.astro         # Layout principal con SEO
│   ├── pages/
│   │   ├── index.astro          # Página principal
│   │   ├── casino.astro         # Página casino
│   │   └── twitter.astro        # Página Twitter
│   └── styles/
│       └── global.css           # Estilos globales
├── public/
│   ├── favicon.svg
│   ├── logo.svg
│   └── robots.txt
└── astro.config.mjs
```

## 🎮 Modos de Juego

| Modo | Descripción |
|------|-------------|
| 🏆 **Ganador** | Selecciona un único ganador al azar |
| 💀 **Eliminación** | Elimina participantes hasta quedar uno |
| 👥 **Equipos** | Divide los participantes en grupos |
| 🔀 **Orden** | Ordena la lista aleatoriamente |
| 🤡 **Troll** | Paradas falsas antes del ganador real |
| ❓ **Misterio** | Nombres ocultos hasta el final |

## 🧞 Comandos

| Comando | Acción |
|---------|--------|
| `npm install` | Instala dependencias |
| `npm run dev` | Servidor de desarrollo en `localhost:4321` |
| `npm run build` | Genera el sitio de producción en `./dist/` |
| `npm run preview` | Previsualiza el build antes de desplegar |

## 📊 SEO

- Schema.org: WebApplication, Organization, FAQPage, HowTo, BreadcrumbList
- Meta tags optimizados para redes sociales
- Sitemap XML generado automáticamente
- Puntuación Lighthouse: 95+

## 📄 Licencia

MIT © 2025 RuletaSorteos.es

---

## 📝 Descripción para GitHub

**Descripción corta (recomendada para el campo "About"):**

> 🎰 Ruleta de sorteos online gratuita. Elige ganadores, crea equipos, elimina participantes. Sistema Provably Fair, personalizable, sin registro. Astro + Tailwind + TypeScript.

**Topics sugeridos:**
`roulette` `sorteo` `random` `picker-wheel` `astro` `tailwindcss` `typescript` `provably-fair` `spanish` `free`
