# 🧩 MvcEstructuraDemo

## 📌 Descripción

Proyecto base creado con **ASP.NET Core Web App (Model-View-Controller)** en Visual Studio 2022.

El objetivo es familiarizarse con la estructura de un proyecto MVC y ejecutar la aplicación en entorno local.

---

## 🎯 Objetivo Académico

Explorar y comprender la estructura básica de un proyecto ASP.NET Core MVC.

---

## 🏗 Estructura del Proyecto

El proyecto incluye las siguientes carpetas principales:

- **Controllers** → Contiene los controladores (HomeController).
- **Models** → Contiene clases de modelo (ErrorViewModel).
- **Views** → Contiene las vistas Razor (.cshtml).
- **wwwroot** → Archivos estáticos (CSS, JS, Bootstrap).
- **Program.cs** → Configuración principal del proyecto.

---

🔄 Flujo del Patrón MVC
El siguiente diagrama muestra cómo funciona el flujo de una petición en ASP.NET Core MVC:

<img width="1536" height="1024" alt="ChatGPT Image Feb 18, 2026, 09_49_06 PM" src="https://github.com/user-attachments/assets/31506d1c-4876-4555-b5bc-7c322fcaa4f5" />

- **Explicación del Flujo:**

- 1- El navegador realiza una solicitud a /Home/Index.

- 2- El HomeController ejecuta la acción Index().

- 3- Se renderiza la vista Index.cshtml.

- 4- La vista utiliza Layout.cshtml como plantilla base.

- 5- Se envía la respuesta HTML final al navegador.

---

## ▶️ Ejecución Local

Al ejecutar el proyecto, la aplicación corre en: https://localhost:7209

(El puerto puede variar según la configuración del entorno.)

---

## 🔄 Flujo MVC

1. El navegador accede a la URL.
2. El enrutamiento dirige la solicitud a `HomeController`.
3. El método `Index()` devuelve la vista correspondiente.
4. La vista se renderiza utilizando `_Layout.cshtml`.

---

## 👤 Integrantes del Grupo 4

Jeurys José Durán Beato - A00115777

Bladimir Ventura - A00115757

Ángel Javier Barrientos - A00115984

Miguel José Saint Hilaire Peña - A00116662

Sean Alcántara Carrera - A00115911 
