
# 📝 Gestor de Tareas con Prioridad

## 🎯 Descripción

Este proyecto es un **gestor de tareas por consola** desarrollado en Python, pensado para facilitar la organización diaria mediante un sistema simple, claro y funcional.

Permite al usuario administrar tareas de forma ordenada, asignándoles una prioridad (alta, media o baja) y controlando su estado (pendiente o completada), manteniendo toda la información guardada de manera segura en un archivo JSON.

---

## 🚀 ¿Qué puedo hacer con este sistema?

* Crear nuevas tareas con prioridad
* Visualizar todas las tareas cargadas
* Marcar tareas como completadas
* Eliminar tareas
* Guardar automáticamente los datos
* Registrar acciones importantes en un archivo de logs

---

## 🗂️ Estructura del proyecto

```
gestor_tareas/
├── main.py           # Menú principal
├── funciones.py      # Lógica del programa
├── tareas.json       # Base de datos de tareas
├── registro.log      # Historial de acciones
├── requirements.txt  # Dependencias
└── README.md         # Documentación
```

---

## ⚙️ Requisitos

* Python 3.x

Para instalar las dependencias:

```
pip install -r requirements.txt
```

---

## ▶️ Cómo ejecutar el programa

Ubicarse en la carpeta del proyecto y ejecutar:

```
python main.py
```

Se mostrará un menú interactivo para operar el sistema de forma intuitiva.

---

## 📌 Estructura de una tarea

```json
{
  "id": 1,
  "titulo": "Estudiar Python",
  "descripcion": "Repasar funciones y listas",
  "prioridad": "media",
  "estado": "pendiente"
}
```

---

## 🧠 Objetivo del proyecto

Demostrar el dominio de conceptos fundamentales de Python como:

* Modularización
* Manejo de archivos
* Estructuras de datos
* Persistencia
* Manejo de errores
* Organización del código

---

## 👩‍💻 Autora

**Paula Girardini**
Proyecto académico desarrollado como parte de evaluación práctica en programación Python.

---

✨ Este sistema fue creado con el objetivo de aprender, practicar y fortalecer habilidades en desarrollo de software utilizando buenas prácticas y herramientas básicas del lenguaje Python.

---

✅ Gestor de tareas listo para organizarte mejor y seguir creciendo en programación.
