
# Proyecto final 2024

Esta aplicación web esta hecha con **python**, **html**, **css** y **javasript** utilizando **django**,**Ionicons**, **Fontawesome** como frameworks (estos dos ultimos son para los iconos personalizados), esta aplicación tiene las funciones basicas y necesarias para el usuario asi como un superadmin para el acceso del administrador del sitio.


## Requisitos 

Para poder utilizar esta aplicación debera tener:

• **Visual Studio Code**

• **Python 3.12 (o superior)** 

• **Django** 

• **Mysql Workbench**
## Requisitos 
1. **Descarga y Descomprime los Archivos**: Descarga y descomprime el archivo `.rar` que contiene el proyecto.
   
2. **Abre el Proyecto en un Editor de Código**: Abre tu editor de código y abre la carpeta descomprimida.

3. **Configura el Entorno Virtual**: Abre una terminal en tu editor de código y ejecuta los siguientes comandos para configurar el entorno de desarrollo:

   ```bash
   python -m venv virtual  # Crea el entorno virtual (o el nombre que prefieras)
   .\virtual\Scripts\activate  # Activa el entorno virtual
   ```
## Comandos

Una vez abierta la terminal realizamos los siguientes comandos:
```bash
python -m venv virtual (creamos el entorno virtual, podemos poner el nombre que queramos)
```
```bash
.\virtual\Scripts\activate (activación del entorno virtual)
```
```bash
django-admin startproject Proyecto (crea el proyecto)
```
```bash
cd .\Proyecto\ (nos posiciona en la carpeta del proyecto)
```
```bash
python manage.py startapp App (crea la app)
```
```bash
python manage.py makemigrations (hace los cambios en la base de datos y los modelos)
```
```bash
python manage.py migrate (Guarda los cambios de los modelos)
```
```bash
python manage.py runserver (activa el sitio web en localhost)
```
## Probando la aplicación

Una vez el servidor esté corriendo, puedes acceder a la aplicación en tu navegador (usualmente en http://127.0.0.1:8000/).

En la página de inicio, encontrarás el navbar que te permitirá registrarte en la aplicación. Si no tienes cuenta, podes crear una; de lo contrario, podes iniciar sesión con tu user.

En el index de la página, se muestra información sobre los productos, incluyendo la ubicación de la tienda.
## ¿Que podes hacer?

- **Gestión de Productos**: Podes crear y eliminar productos en la tienda.
  
- **Gestión de Ventas y Usuarios**: Podes agregar o eliminar ventas y gestionar usuarios.
  
- **Formulario de Contacto**: A través del formulario, podes enviar mensajes y recibir respuestas por correo electrónico (Gmail).

- **Información Adicional**: Accede a información adicional sobre los productos, testimonios de compradores y ofertas exclusivas en la tienda.

- **Preguntas Frecuentes (FAQ)**: Consulta la sección de preguntas frecuentes sobre la tienda.

- **Pie de Página**: En el pie de página (footer), encontrarás enlaces a las políticas de privacidad, términos y condiciones, así como información sobre la empresa en la sección "Sobre Nosotros".
## Autores

- **Melina Alvarado**
- **Alejandro Ovelar**
- **Joaquín Gómez**

---