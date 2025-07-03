# 🗄️ Base de Datos

📝 **Estado:** Borrador — aquí desarrollaremos y gestionaremos la estructura de datos del proyecto final.

---

## 📋 Descripción

Este repositorio contendrá todos los archivos relacionados con la **base de datos del sistema**, incluyendo el diseño de tablas, relaciones, procedimientos almacenados y scripts de inicialización.  
El objetivo es garantizar una estructura sólida, normalizada y preparada para integrarse con el backend.

---

## 🛠️ Tecnologías

- 🧱 **SQL o MongoDB** — Lenguaje para definición y manipulación de datos
- 🛠️ **Workbench / pgAdmin** — Herramientas para modelado y gestión visual
- 📊 **MER / DER** — Diagramas de Entidad-Relación
- 📄 **.sql scripts** — Scripts para creación, inserción y pruebas

---

## 📂 Estructura del proyecto

```bash
/database
  /scripts
    init.sql            # 🛠️ Script para crear la estructura inicial
    seed.sql            # 🌱 Script para insertar datos de prueba
    procedures.sql      # ⚙️ Procedimientos almacenados
    triggers.sql        # ⏰ Triggers (si los hay)
  /models
    modelo.der          # 🧬 Diagrama Entidad-Relación
  README.md              # 📘 Documentación de la base de datos
```

---

## 🔗 Integración

Esta base de datos está diseñada para integrarse directamente con el **backend**
Todos los nombres de tablas, campos y relaciones están documentados y serán consistentes con los modelos del backend.

---

## 📝 Notas

Este README es un **borrador en evolución**. Será actualizado conforme se realicen ajustes en la estructura, se definan nuevas entidades o se implementen mejoras.  
Cualquier sugerencia o mejora es bienvenida 🧩

---