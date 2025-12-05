# RJN PIDAWE

Plataforma educativa que conecta estudiantes con profesores mediante un sistema de recomendación inteligente.  
Proyecto desarrollado con metodología ágil Scrum, en sprints semanales y con un equipo multidisciplinar.

---

## Tecnologías

- **Frontend**: React.js  
- **Backend**: Node.js + Express  
- **Base de datos**: MongoDB  
- **IA/Recomendación**: Python + Scikit-learn  
- **Infraestructura**: AWS / Azure  
- **Herramientas de diseño**: Figma, Canva (opcional)  
- **Gestión de proyectos**: Trello, Notion, Slack/Discord  
- **Control de versiones**: GitHub  

---

## Guía de instalación y despliegue

### Requisitos previos
- Node.js (v18 o superior)  
- MongoDB (local o remoto)  
- Python 3.10+ con librerías de IA (Scikit-learn)

---

## Equipo

- **Scrum Master**: Natalia Cabello / Jaime Vargas (según sprint)  
- **Product Owner**: Raúl Pérez / Natalia Cabello (según sprint)  
- **Developers**: Frontend (React), Backend (Node.js), IA/Data Scientist, DevOps  
- **Soporte y comunidad**: atención al cliente, onboarding de profesores  
- **Marketing y comunicación**: campañas de captación, redes sociales  
- **Legal y compliance**: RGPD, obligaciones fiscales  

---

## Riesgos y medidas preventivas

- **Pérdida de datos** → copias de seguridad periódicas en MongoDB y AWS/Azure.  
- **Errores en despliegue** → validación en *staging* + CI/CD automatizado.  
- **Retrasos en cronograma** → sprints semanales y reuniones de seguimiento.  
- **Conflictos de código** → ramas por funcionalidad + revisiones de código (pull requests).  

---

## ⚠️ Riesgos y medidas preventivas

- **Pérdida de datos** → copias de seguridad periódicas en MongoDB y AWS/Azure.  
- **Errores en despliegue** → validación en *staging* + CI/CD automatizado.  
- **Retrasos en cronograma** → sprints semanales y reuniones de seguimiento.  
- **Conflictos de código** → ramas por funcionalidad + revisiones de código (pull requests).  

---

## Pruebas (QA)

Casos básicos:  
- Registro de usuario (correcto/incorrecto).  
- Agenda (crear, editar, eliminar clase).  
- Chat (enviar/recibir mensajes).  
- Reputación (calificar profesor/estudiante).  

*(Añadir resultados y capturas en `/docs/qa`)*

---

## Cronograma

Duración total: **6 meses**  
- **Mes 1**: investigación y requisitos.  
- **Mes 2-3**: diseño y desarrollo inicial.  
- **Mes 4**: integración de funcionalidades.  
- **Mes 5**: pruebas y validación.  
- **Mes 6**: lanzamiento y marketing.  

---

## Valoración económica

- **Estimación**: 850 horas de desarrollo.  
- **Coste medio**: 25 €/hora → **21.250 €**.  
- **Licencias y hosting**: **1.600 €/año**.  
- **Total inicial**: **22.850 €**.  
- **Inversión realista**: entre **20.000–25.000 €** para cubrir IA, escalabilidad y seguridad.  


### Pasos de instalación
```bash
#Clonar repositorio
git clone https://github.com/TU-USUARIO/RJN-PIDAWE.git

# Entrar en carpeta
cd RJN-PIDAWE

# Instalar dependencias
npm install

# Ejecutar en modo desarrollo
npm run dev

