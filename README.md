## CRUD de Productos con MVC — Autenticación, Validaciones e i18n
Programación Web — Unidad 6: JSP con MVC
Universidad de Santander (UDES) — Ingeniería de Sistemas 2026

## Descripción
Extensión de la aplicación MVC del Post-Contenido 1 que incorpora autenticación de usuarios con HttpSession, validaciones robustas en el servidor con retroalimentación de errores hacia la vista, y soporte de internacionalización (i18n) con ResourceBundle para español e inglés con selector de idioma persistido en sesión.

## Prerrequisitos
Java Development Kit (JDK) 17 o superior
Apache Tomcat 10.x
IntelliJ IDEA
Maven 3.8+
Proyecto mvc-productos del Post-Contenido 1 funcional


## Instrucciones de ejecución
Clonar el repositorio y abrir en IntelliJ
Ejecutar mvn clean package en la terminal
Configurar Tomcat: Run → Edit Configurations → + → Tomcat Server → Local
En Deployment agregar el artefacto .war exploded
Ejecutar y abrir http://localhost:8080/mvc-productos/login
Ingresar con las credenciales: admin / Admin123! o viewer / View456!


## Funcionalidades implementadas
Autenticación de usuarios con HttpSession y credenciales en memoria
Protección de rutas: redirige a /login si no hay sesión activa
Validaciones en el servidor con retroalimentación de errores por campo
Repoblación del formulario con los valores ingresados al haber errores
Internacionalización (i18n) en español e inglés con ResourceBundle
Selector de idioma persistido en sesión


## Capturas de pantalla
Pantalla de login
<img width="1912" height="914" alt="pantallalogin" src="https://github.com/user-attachments/assets/e71148c2-f613-42c8-b63c-17b2f9c0af38" />
Error de credenciales incorrectas
<img width="1912" height="914" alt="credencial incorrecta" src="https://github.com/user-attachments/assets/f2ea3226-9b9e-4102-853b-4478092c6b00" />
Lista de productos con selector de idioma
<img width="1912" height="914" alt="msedge_Q3E0mmqJqP" src="https://github.com/user-attachments/assets/533205e6-5d6e-4388-a82f-7bb5cf47a5b0" />
Lista de productos en inglés
<img width="1912" height="914" alt="msedge_NCsPCI8AD7" src="https://github.com/user-attachments/assets/81e01085-18c4-42e8-b255-192c14ad7580" />
Validación de errores en formulario
<img width="1912" height="914" alt="msedge_W7mpEn1Sit" src="https://github.com/user-attachments/assets/8548da04-e5bc-43f0-a3fb-9b98522d6649" />
