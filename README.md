# 🤖 JoBot

**JoBot** es una aplicación web que te ayuda a entrenar habilidades blandas (*soft skills*) de forma interactiva y divertida, integrando gamificación e inteligencia artificial a través de la API de Gemini.

Desarrollado en equipo bajo **metodología ágil**, con planificación por sprints y gestión de tareas colaborativa.

---

## 🎮 Modos de juego

| Modo | Descripción |
|---|---|
| 🕹️ **Modo Juego** | Practica soft skills a través de dinámicas gamificadas potenciadas por Gemini AI |
| 🎤 **Modo Entrevista** | Simula entrevistas laborales con retroalimentación inteligente generada por Gemini AI |
| 👥 **Modo Multijugador** | Compite contra una IA impulsada por Gemini en desafíos de habilidades blandas |

---

## 🧩 Tecnologías

- **Backend:** Django 4.2+ · Python
- **Frontend:** HTML · CSS · JavaScript
- **IA:** Google Gemini API (`google-generativeai`)
- **Otros:** Pillow · python-dotenv

---

## 🚀 Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/dsalazar444/JoBot.git
cd JoBot
```

### 2. Crear y activar un entorno virtual

```bash
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 4. Configurar variables de entorno

Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:

```env
GEMINI_API_KEY=tu_api_key_aqui
SECRET_KEY=tu_django_secret_key
DEBUG=True
```

### 5. Aplicar migraciones y correr el servidor

```bash
python manage.py migrate
python manage.py runserver
```

Abre tu navegador en `http://127.0.0.1:8000`.

---

## 📁 Estructura del proyecto

```
JoBot/
├── game_mode/          # Lógica del modo juego
├── interview_mode/     # Lógica del modo entrevista
├── multiplayer/        # Lógica del modo multijugador contra IA
├── jobot/              # Configuración principal de Django
├── main/               # Vistas y rutas generales
├── user/               # Gestión de usuarios
├── ui/                 # Componentes de interfaz
├── utils/              # Utilidades compartidas
├── data/               # Datos estáticos o fixtures
├── manage.py
└── requirements.txt
```

---

## 👥 Equipo

- Daniela Salazar
- Viviana 
- Jerónimo Escobar
- Alejandro Jaramillo

---

## 📄 Licencia

Este proyecto fue desarrollado con fines académicos.
