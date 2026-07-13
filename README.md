# 💰 Personal Finance Manager

Aplicación web full stack para gestionar ingresos y gastos personales, visualizar estadísticas y controlar el presupuesto mensual.

## 🚀 Características

- Registro e inicio de sesión de usuarios
- Autenticación mediante JWT
- Gestión de ingresos y gastos
- Categorías personalizadas
- Filtros por fecha
- Dashboard con gráficos
- Estadísticas mensuales
- Exportación de datos
- API REST documentada con Swagger

---

## 🛠️ Tecnologías

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT
- Maven

### Frontend
- React
- TypeScript
- Axios
- Tailwind CSS

### Base de datos
- PostgreSQL

### DevOps
- Docker
- Docker Compose
- GitHub Actions

---

## 📷 Capturas

### Dashboard

![Dashboard](images/dashboard.png)

### Gastos

![Expenses](images/expenses.png)

### Estadísticas

![Stats](images/stats.png)

---

## 📁 Arquitectura

```
src
├── controller
├── service
├── repository
├── model
├── dto
├── security
├── configuration
└── exception
```

---

## ⚙️ Instalación

### Clonar el repositorio

```bash
git clone https://github.com/tuusuario/personal-finance-manager.git
```

### Entrar en el proyecto

```bash
cd personal-finance-manager
```

### Levantar Docker

```bash
docker compose up
```

### Ejecutar Spring Boot

```bash
./mvnw spring-boot:run
```

---

## 📌 Endpoints principales

| Método | Endpoint | Descripción |
|---------|----------|-------------|
| POST | /auth/register | Registro |
| POST | /auth/login | Login |
| GET | /expenses | Obtener gastos |
| POST | /expenses | Crear gasto |
| PUT | /expenses/{id} | Actualizar gasto |
| DELETE | /expenses/{id} | Eliminar gasto |

---

## 🧪 Tests

Ejecutar:

```bash
./mvnw test
```

---

## 📊 Futuras mejoras

- [ ] Aplicación móvil
- [ ] Notificaciones
- [ ] Exportación PDF
- [ ] IA para predicción de gastos
- [ ] Integración bancaria

---

## 👨‍💻 Autor

**Tu Nombre**

LinkedIn: https://linkedin.com/in/tuusuario

GitHub: https://github.com/tuusuario
