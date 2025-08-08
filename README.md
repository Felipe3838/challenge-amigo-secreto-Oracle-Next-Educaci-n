# :twisted_rightwards_arrows: Sorteo de Amigo Secreto
## 📑 Índice 📑

- [Sorteo de Amigo Secreto](#sorteo-de-amigo-secreto)
- [Descripción del Proyecto](#books-descripción-del-proyecto)
- [Funcionalidades](#wrench-funcionalidades)
- [Tecnologías utilizadas](#🧠-tecnologías-utilizadas)
- [Estructura del Proyecto](#card_file_box-estructura-del-proyecto)
- [Cómo usar este proyecto](#cómo-usar-este-proyecto)
- [Validaciones implementadas](#computer-validaciones-implementadas)
- [Posibles mejoras futuras](#💡-posibles-mejoras-futuras)
- [Autor](#👨‍💻-autor)
- [Licencia](#📃-licencia)
<p align="center">
  <img src="https://static.skillshare.com/uploads/video/thumbnails/c38251fc34fe43812b476c376c5d6945/1280-720" width="200">
</p>

**Sorteo de Amigo Secreto** es una **aplicación web interactiva** desarrollada con **JavaScript**, **HTML** y **CSS**, y propuesta por **Oracle Next-Education** – curso de tecnología, cuyo objetivo principal es **fortalecer y promover las habilidades en lógica de programación** y, por supuesto, aplicar los conocimientos vistos en los cursos **Lógica de programación: sumérgete en la programación con JavaScript** y **Lógica de programación: explorar funciones y listas**.  
Esta herramienta permite simular el juego de "amigo secreto o amigo aleatorio", donde se agregan nombres a una lista para luego realizar un sorteo aleatorio y seleccionar un participante.

---

## :books: Descripción del Proyecto

Este proyecto fue creado como parte de un desafío de aprendizaje,con el obejtivo de practicar lo aprendido e interactuar con:

- El **Modelo de Objetos del Documento (DOM)** con JavaScript.
- **Validaciones de entradas de texto segun los requerimientos propuestos en el desafío**.
- Uso de **estructuras de datos** como listas/arrays para almacenar los nombres de las personas o los amigos ingresados.
- **Selección aleatoria** con lógica de programación.
- uso de **condicionales,cliclos y funciones**que interactuen según la aplicación de la lógica del autor del proyecto.
- entre **otras.**

---

## :wrench: Funcionalidades
<p align="center">
    <img src="https://i.postimg.cc/d1gj35GR/Captura-de-pantalla-2025-08-08-172029.png" width="500">
  </p>
Primero se crea una lista llamada `amigos` donde se almacenarán todos los nombres registrados.  

1. :white_check_mark:**Agregar amigos a la lista** 
   Permite registrar nuevos nombres en `listanombreAmigosParaSortear`, validando que no estén vacíos,no aceptando números ni carácteres especiales y limpiando el campo tras añadirlos.  

2. :white_check_mark:**Mostrar la lista de amigos**  
   Muestra en pantalla los nombres del arreglo `amigos` en una lista de forma visual para el ususrio, evitando duplicados y actualizando constantemente.  

3. :white_check_mark:**Sortear un amigo**  
   Selecciona aleatoriamente un nombre de `amigos` y lo muestra en pantalla,y se concluye así el objetivo principal del programa. 
---

## 🧠 Tecnologías utilizadas

- **HTML**  
  <p align="center">
    <img src="https://github.com/user-attachments/assets/58204778-1132-4f2f-80ec-8b69f98f0407" width="200">
  </p>

- **CSS**  
  <p align="center">
    <img src="https://github.com/user-attachments/assets/0c70133e-2f53-4313-bbab-1390918f51b5" width="200">
  </p>

- **JavaScript**  
  <p align="center">
    <img src="https://github.com/user-attachments/assets/4ada2a2f-c240-4d67-a157-ffcb0970afc0" width="200">
  </p>
---

## :card_file_box: Estructura del Proyecto

```plaintext
📁 Proyecto-Amigo-Secreto/
├── index.html         # Estructura principal
├── style.css          # Estilos visuales para la página.
├── script.js          # Lógica e interactividad en JavaScript
└── README.md          # Documentación del proyecto
```

---

## 🛠️ ¿Cómo usar este proyecto?

1. **Clona el repositorio o si es preferible descargarlo en archivo RAR para probar sin necesidad de clonarlo:**

```bash
git clone https://github.com/Felipe3838/challenge-amigo-secreto-Oracle-Next-Educaci-n
```

2. **Luego abre el archivo `index.html` en tu navegador que está dentro de la carpeta donde clonaste el proyecto** (doble clic para iniciarlo y abrir el el navegador).

3. :computer:**Usa la aplicación**:

- Escribe un nombre en el campo de texto.
- los nombres que vayas agrgando,irán apareciendo en la pantalla.
- Haz clic en **"Agregar amigo"**.
- Una vez que haya varios nombres, haz clic en **"Sortear amigo"** para seleccionar un amigo secreto al azar.

---

## :computer: Validaciones implementadas

- ❌ No se permiten campos vacíos.Si el usuario le da a **añadir** sin haber escrito un nombre,hará la validación correspondiente.
- ❌ No se permiten caracteres especiales ni números.Si el usuario escribe **números o caracteres especiales**hará la validación correspondiente.
- ❌ No se permiten nombres repetidos.Hsta el momento si escribes **Felipe** y vulves y agrgas a **Felipe** hara la validación correspondiente y no dejará agrgar nombres repetidos.

---

## 💡 Posibles mejoras futuras

- Agregar estilos visuales más atractivos.
- Implementar la opción de **eliminar nombres**en caso de un posible error de ingreso.
- Añadir un botón para **reiniciar el sorteo**.y por supuesto limpiar los datos ya ingresados despues del sorteo

---

## 👨‍💻 Autor

- **Brayan Ferlipe Muñoz S**
- GitHub: [@Felipe3838](https://github.com/Felipe3838)

---

## 📃 Licencia

Este proyecto se ha desarrollado con fines educativos aplicables a los conocimientos visto dentro del curso **Oracle Nest Education**. Puedes usarlo, modificarlo y compartirlo libremente.

---
