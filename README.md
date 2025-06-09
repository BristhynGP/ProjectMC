# MI CULTIVO PROGRESA
________________________________________  
## Introducción y Objetivos  
Mi Cultivo Progresa es una web ͏cuyo objetivo es hacer más fácil la compra y venta de productos del campo directamente entre los campesinos y los consumidores. La idea busca quitar los intermediarios ͏injustos y ͏darles un canal claro, fácil y justo para vender sus productos de ͏la granja. El sistema deja͏ que vendedores registrados (campesinos͏) puedan mostrar sus cosas a precios justos, mientras que los compradores pueden buscar, elegir y comprar cosas ͏locales ͏desde la página͏ web.  

### Objetivos principales:  
- Innovar los métodos y procesos de ventas de los campesinos permitiéndoles gestionar y publicar sus productos fácilmente.  
- Garantizar precios razonables tanto para el vendedor como para el consumidor.  
- Digitalizar el proceso de comercialización rural.  
- Facilitar el acceso a productos frescos, locales y sostenibles para cualquier persona.  

________________________________________  
## Alcance del Proyecto  
Este proyecto está diseñado para implementarse en fases, priorizando el desarrollo de un MVP funcional con las siguientes características clave:  

### Versión 1 - MVP  
- Registro y acceso de usuarios campesinos.  
- Publicación de productos con sus imágenes, precios y descripciones.  
- Catálogo público visible para posibles compradores.  
- Interfaz web con navegación amigable para los usuarios.  
- Base de datos SQLite para el manejo de datos de manera local.  

### Versión 2 - Planeada  
- Formulario amigable para el registro de usuarios.  
- Formulario para la creación publicación de productos del campo.  
- Panel administrativo para modificación de usuarios y productos.  
- Implementación de filtros por tipo de producto.  

---

## Estructura del Proyecto  

```
ProjectMC/
├── manage.py                  → Comando principal del proyecto
├── db.sqlite3                 → Base de datos local por defecto
├── requirements.txt           → Lista de dependencias necesarias
├── AppMC/                     → Aplicación principal del sistema
│   ├── migrations/            → Migraciones de base de datos
│   ├── templates/             → Plantillas HTML (interfaz de usuario)
│   ├── static/                → Archivos estáticos (CSS, JS, imágenes)
│   ├── models.py            → Definición de modelos(usuarios, post, relacion)
│   ├── views.py               → Lógica de las vistas (controladores)
│   ├── urls.py                → Rutas locales de la app
│   └── admin.py               → Configuración de modelos en panel de administración
```

---

## Instrucciones de Instalación y Ejecución  
**Requisitos previos para la ejecución del programa:**  
- Python 3.8 o superior.  
- Djamgo.  
- Pip.  
- Navegador actualizado.  

### Pasos para ejecución local  

**Crear un entorno virtual para le ejecución de manera local:**  
```bash
python -m venv env        # Crear entorno virtual
```

**Activación:**  
```bash
source env/bin/activate       # Linux/macOS  
.\env\Scripts\ctivate        # Windows
```

**Instalar dependencias:**  
```bash
pip install -r requirements.txt
```

**Aplicar migraciones:**  
```bash
python manage.py makemigrations  
python manage.py migrate
```

**Ejecutar el servidor:**  
```bash
python manage.py runserver
```

**Abrir navegador en:**  
```
http://127.0.0.1:8000/
```

---

## Descripción de la App  
**Funciones clave:**  
- **Inicio:** Muestra ͏la pantalla de bienvenida al sistema.  
- **Plantillas͏:** Plantillas HTML en Ap͏pMC/tem͏plates/ que muestra los diseños principales de la página web.  
- **Modelos:** Define los modelos de datos para cultivos u otras cosas ͏de agricultura͏.  
- **Vistas:** Lógica que trata peticiones HTTP y hace respuestas.  
- **Static:** Encontramos los documentos CSS y JavaScript que le dan estilo y funcionalidad a la página web.  

---

## Tecnologías Utilizadas  

| Tecnología  | Descripción                     |
|-------------|----------------------------------|
| Python      | Lenguaje principal               |
| Django      | Framework web                    |
| SQLite3     | Base de datos local              |
| HTML/CSS    | Interfaz de usuario (frontend)   |
| JavaScript  | Interactividad básica            |
| Git         | Control de versiones             |

---

## Estado Actual del Proyecto  
- Proyecto correctamente estructurado y funcional en local.  
- Interfaz básica de inicio lista.  
- Proyecto Web listo para integrar modelos de datos.
