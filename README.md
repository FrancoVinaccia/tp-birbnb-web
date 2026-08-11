# Birbnb 🏠

Plataforma web de reservas de alojamientos temporales, desarrollada como
TP de **Desarrollo de Software (UTN FRBA, 2025)**.

🌐 **[Ver demo en vivo](https://tp-birbnb-web.vercel.app/)**

> ⏳ La primera carga puede demorar unos segundos mientras el servidor
> gratuito de Render se inicia.

## ✨ Funcionalidades

- Publicación y administración de propiedades
- Búsqueda de alojamientos con filtros
- Flujo completo de reservas (solicitud, confirmación, cancelación)
- Sistema de notificaciones para huéspedes y anfitriones

## 🛠️ Stack

- **Backend:** Node.js + Express
- **Frontend:** Next.js + React
- **Testing:** Jest (unitario e integración) · Cypress (E2E)
- **Deploy:** Render (API) · Vercel (frontend)

## ✅ Testing

El proyecto incluye una suite de tests automatizados en tres niveles:
unitarios, de integración y end-to-end.

​```bash
npm test          # unitarios e integración
npx cypress run   # E2E
​```

## 🚀 Levantarlo localmente

​```bash
git clone https://github.com/FrancoVinaccia/tp-birbnb-web.git
cd tp-birbnb-web
npm install
npm start
​```
