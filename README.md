# 📚 Desafío Libros – Trabajando con Lambdas y Streams

**Desafío Libros** es una aplicación desarrollada en Java con Spring Boot, como parte del programa de formación de Alura Latam – Oracle. El objetivo del proyecto es buscar libros a partir de un título (o parte de él) y, mediante una API externa, obtener datos relevantes sobre el autor y el libro, como:

* Nombre del autor y fecha de nacimiento.
* Título completo, idioma y cantidad total de descargas.

Este proyecto sirvió como práctica de temas avanzados de Java, como programación funcional con **lambdas**, **streams**, manejo de **fechas**, y consumo de APIs externas.

---

## 🚀 Tecnologías usadas

* **Java**
* **Spring Boot**
* **Maven** (gestor de dependencias)
* **Jackson** (para convertir JSON en objetos Java)

---

## 🧠 ¿Qué se aprendió en este proyecto?

Durante el desarrollo se trabajó con:

* Spring Boot y su estructura de proyectos.
* Consumo de APIs externas.
* Conversión de datos JSON usando Jackson.
* Modelado de datos (autor, libro, estructura de resultados).
* Funciones Lambda y uso de Streams.
* API de fechas para manipular y mostrar fechas con formato.
* Generación de estadísticas y filtrado de datos.
* Principios de buenas prácticas de programación.

---

## 📂 Estructura del proyecto

```
src/
└── main/
    └── java/
        └── com.aluracursos.desafio/
            ├── model/
            │   ├── Datos.java
            │   ├── DatosAutor.java
            │   └── DatosLibro.java
            ├── principal/
            │   └── Principal.java
            ├── service/
            │   ├── ConsumoAPI.java
            │   ├── ConvierteDatos.java
            │   └── IConvierteDatos.java
            └── DesafioApplication.java
pom.xml
```

---

## 💻 Cómo ejecutar el proyecto

> ⚠️ Aún no se ha documentado el paso a paso para la instalación y ejecución. Si deseas colaborar agregando esta información, ¡eres bienvenido!

Requisitos mínimos:

* JDK 17 o superior
* Maven
* IDE como IntelliJ IDEA o Eclipse

---

## 🛠️ Estado del proyecto

✅ Proyecto finalizado.

---

## 🤝 Contribuciones

Si te interesa colaborar o mejorar este proyecto, puedes abrir issues o enviar pull requests.

---

## 👩‍💻 Autora

Paola E. Bastida
Alumna de Alura Latam – Oracle | Grupo G8
📧 Contacto: [paobastidaqa@gmail.com](mailto:paobastidaqa@gmail.com)
