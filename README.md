# Sistema Inteligente de Recomendación Educativa

## Descripción
Plataforma web inteligente para la recomendación de estrategias de enseñanza y herramientas digitales mediante Machine Learning.

El sistema permite:
- Gestión de usuarios
- Administración de catálogos
- Registro de experiencias educativas
- Generación automática de recomendaciones
- Entrenamiento de modelos de inteligencia artificial

---

# Requisitos previos

- Python 3.11 o superior
- MySQL Server
- Git (opcional)
- Navegador web moderno

---

# Tecnologías utilizadas

## Backend
- Python
- Flask

## Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

## Inteligencia Artificial
- Scikit-learn
- Random Forest
- KNN
- Naive Bayes

## Base de datos
- MySQL
- phpMyAdmin

---

# Pasos de instalación

## 1. Clonar o descargar el proyecto

```bash
git clone URL_DEL_PROYECTO
```

O descargar manualmente la carpeta del proyecto.

---

## 2. Crear entorno virtual

```bash
python -m venv venv
```

### Activar entorno virtual

### Windows
```bash
venv\Scripts\activate
```

### Linux
```bash
source venv/bin/activate
```

---

## 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 4. Configurar la base de datos

1. Crear una base de datos en MySQL.
2. Importar el archivo `.sql` del proyecto.
3. Configurar usuario y contraseña en el archivo de conexión.

Ejemplo:

```python
host="localhost"
user="root"
password="1234"
database="sistema_recomendador"
```

---

## 5. Ejecutar el sistema

```bash
python app.py
```

---

## 6. Abrir en navegador

Ingresar a:

```text
http://127.0.0.1:5000
```

---

# Funcionalidades principales

- Inicio de sesión
- Gestión de usuarios
- Gestión de catálogos
- Captura de experiencias
- Recomendación automática mediante Machine Learning
- Administración de estrategias y herramientas educativas

---
