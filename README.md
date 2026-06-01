# ¿Dónde pongo mis pesos? — Simulador de Inversiones Argentina

## 🚀 Deploy en Netlify (5 minutos)

1. Subí esta carpeta a un repo GitHub
2. Netlify > "Add new site" > "Import from GitHub"
3. Build command: (vacío)
4. Publish directory: `.`
5. Deploy site ✅

## 💰 Estrategia de monetización (en orden de prioridad)

### 1. Google AdSense — ingreso desde el día 1
- Crear cuenta en adsense.google.com
- Verificar el sitio (requiere algo de tráfico primero, ~100 visitas/día)
- Reemplazar los dos `<div class="ad-unit">` con el código real de AdSense
- Los sitios de finanzas personales tienen CPM alto ($2–8 USD por 1000 impresiones)

### 2. Afiliados — ingreso por registro
Ya están integrados los links. Registrarse en cada programa:
- **InvertirOnline**: programa de referidos en su web (pagan por cuenta abierta)
- **Buenbit**: programa de afiliados en buenbit.com/afiliados
- **Lemon Cash**: programa en lemon.me/referidos
- **Naranja X**: contactar directamente a su equipo de marketing

Cada registro referido puede generar $5–20 USD de comisión.

### 3. Sponsorships directos
Con 1000+ usuarios/mes, contactar directamente a:
- Fintech argentinas (Ualá, Mercado Pago, Personal Pay)
- Brokers (PPI, Balanz, Cocos Capital)
- Ofrecer un banner destacado o mención por $100–300 USD/mes

## 📊 Proyección de ingresos (conservadora)

| Métrica           | Mes 1  | Mes 3  | Mes 6   |
|-------------------|--------|--------|---------|
| Visitas/mes       | 500    | 3.000  | 10.000  |
| Ingreso AdSense   | $1 USD | $10 USD| $40 USD |
| Ingreso afiliados | $10 USD| $60 USD| $200 USD|
| **Total**         | **$11**| **$70**| **$240**|

El crecimiento es exponencial con viralización en Twitter/X.

## 📡 APIs usadas (todas gratuitas)

- **BCRA**: api.bcra.gob.ar — tasas oficiales (sin key)
- **DolarAPI**: dolarapi.com — cotizaciones del dólar (sin key)
- **Binance**: api.binance.com — precio Bitcoin en tiempo real (sin key)
- **Merval**: datos estimados (mejorar con API de IOL en v2)

## 🗺 Roadmap v2

- [ ] Agregar ETH, stablecoins, FCI
- [ ] Historial personal (Firebase Auth)
- [ ] Alertas por email cuando el dólar sube X%
- [ ] Versión mobile PWA
- [ ] Blog de educación financiera (SEO)

## 🔧 Personalización

Para cambiar los links de afiliados, buscar en index.html:
```
href="https://www.invertironline.com/?ref=simulador"
```
Reemplazar con tu propio código de referido de cada plataforma.
