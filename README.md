# 🌐 Mi Portafolio Fullstack + Data Science

Este repositorio reúne diversos proyectos personales desarrollados con tecnologías modernas en el stack **frontend, backend y data science**. Cada carpeta representa una parte clave del portafolio.

---

## 📁 Estructura del Repositorio


---

## 🖥️ Frontend (`frontend/`)
Aplicación web creada con **React** o **Next.js** que consume las APIs desarrolladas en los proyectos backend. Incluye:

- Rutas protegidas
- Gestión de estado
- Gráficos interactivos
- Diseño responsivo con Tailwind CSS o Material UI

👉 [Ir a frontend](./frontend)

---

## 🔧 Backend Spring Boot (`backend-spring/`)
API REST robusta desarrollada con **Spring Boot**, ideal para lógica empresarial compleja. Características:

- Seguridad con JWT
- CRUD de entidades
- Validación de datos
- Documentación con Swagger

👉 [Ir a backend-spring](./backend-spring)

---

## ⚙️ Backend Node.js (`backend-node/`)
Microservicio o API ligera desarrollada con **Express.js**. Ideal para integraciones rápidas, autenticación o conexiones con Python. Incluye:

- Endpoints REST
- Middlewares personalizados
- Conexión con scripts de Python o servicios externos

👉 [Ir a backend-node](./backend-node)

---

## 📊 Data Science (`data-science/`)
Módulo de análisis de datos y machine learning usando Python. Contiene:

- `notebooks/`: Exploración de datos y pruebas
- `modelos/`: Modelos entrenados (pickle, joblib, etc.)
- `scripts/`: Automatización de inferencia o procesamiento

👉 [Ir a data-science](./data-science)

---

## 📚 Documentación (`docs/`)
Diagramas, especificaciones técnicas, flujos de datos, y documentación general del sistema:

- Arquitectura del sistema
- Diagrama entidad-relación
- Swagger JSON/YAML
- Descripción del stack y decisiones de diseño

👉 [Ir a docs](./docs)

---

## 🚀 Cómo correr los proyectos

Cada carpeta incluye su propio `README.md` con instrucciones específicas para correr cada módulo. En general:

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend Spring
cd backend-spring
./mvnw spring-boot:run

# Backend Node
cd backend-node
npm install
node index.js

# Data Science (opcional)
cd data-science/scripts
python main.py
