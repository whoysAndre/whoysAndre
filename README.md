<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=André%20Rodrigo&fontSize=72&fontColor=fff&animation=fadeIn&fontAlignY=40&desc=Backend%20Developer%20·%20NestJS%20·%20TypeScript%20·%20Node.js&descAlignY=62&descAlign=50&descSize=16"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=800&color=7C3AED&center=true&vCenter=true&width=700&lines=Backend+Developer+con+NestJS+%2B+TypeScript+%F0%9F%9A%80;APIs+REST+con+auth%2C+guards+y+roles;Docker+%7C+PostgreSQL+%7C+JWT+%7C+Swagger;IA+integrada+con+Groq+en+producción;Proyectos+reales+y+desplegados)](https://git.io/typing-svg)

</div>

<br/>

---

## 🧑‍💻 Sobre mí

Soy desarrollador backend de Lima, Perú 🇵🇪 especializado en **NestJS y TypeScript**.

Construyo APIs REST con autenticación, autorización por roles, documentación con Swagger y contenedorización con Docker. Uso **Next.js** cuando necesito que la funcionalidad sea visible y demostrable.

Mi enfoque: **proyectos reales, desplegados y listos para mostrar en entrevista.**

```typescript
const andré = {
  rol:         "Backend Developer — NestJS · TypeScript",
  principal:   ["NestJS", "TypeScript", "TypeORM", "PostgreSQL", "Prisma", "JWT"],
  frontend:    ["Next.js", "React", "Tailwind CSS"],
  devops:      ["Docker", "Docker Compose", "Render", "Vercel"],
  ia:          ["Groq (llama-3.1)"],
  ahora:       "Testing con Jest y arquitectura limpia en NestJS",
};
```

---

## 🚀 Proyectos

### 🏠 Airyty — Plataforma de alquiler vacacional (Fullstack)
> Clon funcional de Airbnb — el proyecto más representativo de mi nivel técnico

**Backend:** NestJS · TypeScript · Prisma · PostgreSQL · JWT · Passport.js · Cloudinary · Stripe (simulado)

**Frontend:** Next.js 16 · React 19 · Tailwind CSS 4 · shadcn/ui · Zustand · React Hook Form · Zod

- Arquitectura modular: auth, listings, bookings, payments, reviews, cloudinary
- Auth completo con **JWT + Guards + estrategias Passport.js** y roles (GUEST / HOST)
- Lifecycle completo de reservas con máquina de estados: `PENDING → CONFIRMED → COMPLETED / CANCELLED`
- Detección de conflictos de fechas — sin solapamientos en reservas
- Pagos con **transacciones atómicas** (`prisma.$transaction`) — pay/refund en un solo bloque
- Subida de imágenes a **Cloudinary** con cleanup automático al eliminar listings
- Frontend con drag & drop, galería de imágenes, filtros y paginación
- Deploy completo: **Render (backend) + Vercel (frontend) + Neon (PostgreSQL)**

[![Backend](https://img.shields.io/badge/Backend-NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://github.com/whoysAndre/airyty-backend.git)
[![Frontend](https://img.shields.io/badge/Frontend-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://github.com/whoysAndre/airyty-frontend.git)
[![Demo](https://img.shields.io/badge/Demo-Live-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://airyty-frontend.vercel.app)

---

### 🛠️ ArtService — Marketplace de desarrolladores freelance
> API REST para que clientes descubran y contacten desarrolladores — arquitectura producción-ready

**Stack:** NestJS 11 · TypeScript · PostgreSQL · Prisma ORM · Google OAuth2 · JWT · Cloudinary · Resend · Swagger

- Auth sin contraseñas: **Google OAuth2 + JWT**
- Roles diferenciados (CUSTOMER / DEVELOPER) con JWT actualizado al cambiar de rol
- Búsqueda y filtros de perfiles por especialidad con paginación
- Subida de foto de perfil y proyectos de portafolio a **Cloudinary**
- Envío de emails a desarrolladores mediante **Resend**
- Reviews con restricción de unicidad (`@@unique` a nivel de DB)
- Validación de env vars con **Joi** al inicio — crash-fast si falta algo
- Documentación interactiva con **Swagger UI** + `persistAuthorization`

[![Backend](https://img.shields.io/badge/Backend-NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://github.com/whoysAndre/artservice-back.git)
[![API Docs](https://img.shields.io/badge/API_Docs-Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://artservice-back.onrender.com/docs)

---

## 📊 Estadísticas

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=whoysAndre&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&title_color=7C3AED&icon_color=7C3AED"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=whoysAndre&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&title_color=7C3AED"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=whoysAndre&theme=tokyonight&hide_border=true&ring=7C3AED&fire=7C3AED&currStreakLabel=7C3AED"/>
</div>

---

## 🗺️ Roadmap 2026

| Estado | Meta |
|--------|------|
| ✅ | NestJS — Guards, interceptores, pipes, módulos |
| ✅ | Auth completo con JWT + Passport.js + roles |
| ✅ | TypeORM + Prisma + PostgreSQL — relaciones, migraciones |
| ✅ | Docker + Docker Compose |
| ✅ | Deploy fullstack en producción |
| ✅ | Integración de IA con Groq en NestJS |
| ✅ | Google OAuth2 con Passport.js |
| ✅ | Transacciones atómicas con Prisma |
| ⬜ | Testing con Jest en NestJS |
| ⬜ | Arquitectura limpia y hexagonal |
| ⬜ | Microservicios con NestJS |

---

## 🤝 Conectemos

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-aquiño-valdez-5a314624b)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://rodrigoaquinovalportfolio.netlify.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yellowcata2121@gmail.com)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=twinkling"/>
</div>
