# Agenda-de-Contactos
Aplicación de Agenda de Contactos en Python con Tkinter y SQLite (Proyecto Final del curso de Python).

---

## 🚀 Funcionalidades

- ➕ Agregar un contacto (nombre, apellido, celular, email).  
- 📋 Listar todos los contactos en pantalla.  
- ✏️ Modificar un contacto existente.  
- ❌ Eliminar un contacto.  

### ✅ Validaciones implementadas
- Nombre y apellido no vacíos y solo letras.  
- Celular numérico obligatorio.  
- Email con formato válido.  
- Persistencia en `contactos.db`.  

---

## 🖥️ Ejecución

### Opción A – Ejecutar con Python
1. Clonar este repositorio  
   ```
   git clone https://github.com/tu-usuario/Agenda-de-Contactos.git
2. Entrar a la carpeta del proyecto

    ```
    cd Agenda-de-Contactos
    ```
3. cutar el programa

    ```
    python gui.py
    ```
    *Requiere Python 3.x y Tkinter instalado).*

### Opción B – Crear el ejecutable
Este proyecto puede convertirse en un archivo .exe utilizando auto-py-to-exe.
En el README original del curso está explicado el proceso completo de creación del ejecutable.

---


## 📂 Estructura del proyecto

```
Agenda-de-Contactos/
├── gui.py              # archivo principal - interfaz de usuario
├── db/                 # carpeta de base de datos
│   ├── contactos.db    # base de datos SQLite
│   └── db.py           # lógica de conexión y operaciones de BD
├── mods/               # módulos de ventanas
│   ├── alta.py         # ventana para agregar contactos
│   ├── eliminar.py     # ventana para eliminar contactos
│   ├── listar.py       # ventana para mostrar todos los contactos
│   └── modificar.py    # ventana para editar contactos existentes
└── README.md           # documentación del proyecto
```

---

## 📸 Capturas de pantalla

.

---

## 📚 Tecnologías utilizadas

- Python 3.x

- Tkinter

- SQLite

- auto-py-to-exe

---

## 👨‍💻 Autor
- Diego Tutor

**Proyecto final del Curso Introductorio de Python.**


