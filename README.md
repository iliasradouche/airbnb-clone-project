# airbnb-clone-project

A backend system that replicates key Airbnb features: user management, property listings, bookings, payments, and reviews. Built for scalability, performance, and security.

---

##  Team Roles

- **Backend Dev**: API endpoints, logic, integrations.
- **DB Admin**: Schema design, indexing, optimization.
- **DevOps**: Docker, CI/CD, deployments.
- **QA**: Testing, bug tracking, validation.

---

##  Tech Stack

- **Django**: Web framework
- **DRF**: REST API support
- **PostgreSQL**: Relational DB
- **GraphQL**: Flexible querying
- **Celery + Redis**: Async tasks & caching
- **Docker**: Containerized dev/deploy
- **GitHub Actions**: CI/CD pipeline

---

##  Database Design

- **User**: `id`, `email`, `password`, `name`
- **Property**: `id`, `owner`, `title`, `location`, `price`
- **Booking**: `id`, `user`, `property`, `check_in/out`
- **Review**: `id`, `user`, `property`, `rating`, `comment`
- **Payment**: `id`, `booking`, `amount`, `status`

**Relations**:  
Users own properties, make bookings & reviews. Bookings and payments link to properties.

---

##  Features

- **Auth**: Register/login, profile mgmt
- **Properties**: CRUD listings
- **Bookings**: Make/manage reservations
- **Payments**: Transaction handling
- **Reviews**: Leave feedback
- **Optimizations**: Indexing, caching

---

##  API Security

- **Auth**: JWT-based
- **Authorization**: Role checks
- **Rate Limiting**: Prevent abuse
- **Data Security**: Encrypt sensitive info

---

##  CI/CD Pipeline

Automated build, test & deploy via:
- **GitHub Actions**
- **Docker**
- **Optional deploy**: Heroku, AWS, etc.
