# POS System

Sistema de punto de venta **multi-stack**, válido para cualquier negocio y nicho. Cada versión implementa las mismas funcionalidades con tecnologías distintas.

## Versiones

| Versión | Tech stack | Tipo | Estado |
|---|---|---|---|
| [`astro/`](withastro/) | Astro + Prisma + Bun | Web SSR | 🚧 En desarrollo |
| [`nuxt/`](withnuxt/) | Nuxt + Prisma + Yarn | Web SSR | 🚧 En desarrollo |
| [`python/`](withpython/) | Python + CustomTkinter + SQLite | Desktop | ✅ Completa |

## Funcionalidades comunes

- Multiusuario con roles (admin / vendedor)
- Ventas con código de barras
- Clientes y cuenta fiado
- Cierre de caja diario
- Reportes (productos más vendidos, top 5, deudas)
- Respaldo automático en la nube

## Instalación

```bash
# Python (desktop)
cd python && pip install -r requirements.txt && python main.py

# Nuxt (web SSR)
cd nuxt && yarn install && yarn dev
```

## Estructura

```
pos-system/
├── python/      # Desktop — Python + CustomTkinter + SQLite
├── nuxt/        # Web SSR — Nuxt + Prisma
└── README.md
```
