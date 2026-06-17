# landing-flotillas-plasencia

Landing del track B2B Flotillas del Motor de Atribución de Grupo Plasencia Automotriz.

**URL producción (cuando Felipe TI registre CNAME):** https://flotillas.grupoplasencia.com
**URL provisional GitHub Pages:** https://mktgrupoplasenciaautomotriz.github.io/landing-flotillas-plasencia/

## Stack

Vanilla HTML/CSS/JS monolito (patrón consistente con landing-hyundai/stellantis/gac/seminuevos). GitHub Pages desde `/docs/`.

## Diferencias vs SPAs D2C del piloto

Esta SPA es **B2B cross-marca** (no D2C de una marca dealer). Capturas:

- Empresa + RFC + email corporativo
- # unidades de la flotilla (gate ICP A/AA/AAA)
- Industria + modalidad financiamiento + ciclo renovación
- Lineup ponderado de 7 marcas del grupo (Ford, Mazda, Stellantis, Hyundai, GAC, Changan, GWM)

## Endpoints

- POST `https://crm-plasencia.grupo-plasencia-automotriz.workers.dev/api/lead/flotillas`

## Tracking

- GTM container: `GTM-WKV7LZ7T`
- GA4 property: `G-47Y5H2PJVP`
- Meta Pixel: `1007710711647839`

## Deploy

GitHub Pages desde `main`, folder `/docs`. El CNAME se registra automáticamente al detectar el archivo `CNAME`.

## Source of truth de docs

Audit + plan de build: `grupo-plasencia-docs/00-context/Flotillas-SPA-B2B-Audit-Y-Plan-Build.md`
