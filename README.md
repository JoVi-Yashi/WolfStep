# **WolfStep – Sistema de Gestión de Calzado con Instinto de Líder**

**Gestión poderosa, precisa y diseñada para crecer**

----------

##  **Descripción General**

**WolfStep** es un sistema de gestión de calzado creado para brindar un control total, firme y eficiente sobre inventarios de zapatos para **niños, jóvenes y caballeros**. Inspirado en la disciplina, fortaleza y armonía de la manada, WolfStep combina **potencia, orden y elegancia funcional** para ofrecer una experiencia de administración moderna, estable y de alto rendimiento.

El sistema permite gestionar cada aspecto del negocio: desde el registro de modelos, tallas y colores, hasta el seguimiento de existencias, movimientos internos y procesos de venta. Su arquitectura está pensada para adaptarse al crecimiento del negocio y responder incluso ante operaciones demandantes.

## **Tecnologías Utilizadas**

### **Frontend**

-   **Vue.js**  
    Utilizado para construir una interfaz moderna, reactiva y fácil de usar.  
    Permite una experiencia fluida, rápida y altamente personalizable.
    

### **Backend**

-   **Laravel (PHP)**  
    Elegido por su solidez, escalabilidad y estructura limpia.  
    Facilita la creación de APIs seguras, ordenadas y de alto rendimiento.
    

### **Base de Datos**

-   **PostgreSQL**  
    Base de datos robusta y confiable, ideal para manejar datos estructurados, relaciones complejas y alto volumen de información.

## **Características Principales**

-    **Gestión de Inventario Completa**  
    Manejo de modelos, tallas, colores y categorías.
    
-    **Control de Existencias**  
    Consulta detallada de stocks, alertas y movimientos entre almacenes.

-	**Control de Categorías**
	Manejo de tipos de calzado, con sus propias características.



## **Instalación y Configuración**

### **1. Clonar el repositorio**

`git clone https://github.com/tu-usuario/wolfstep.git cd wolfstep` 

### **2. Backend – Laravel**

`cd backend
composer install cp .env.example .env php artisan key:generate` 

Configura tus credenciales de PostgreSQL en `.env`.

Ejecuta migraciones:

`php artisan migrate` 

Inicia el servidor:

`php artisan serve` 

### **3. Frontend – Vue.js**

`cd frontend`
`npm install`
`npm run dev`


## **Pruebas**

### Backend

`php artisan test` 

### Frontend

`npm run test`


## **Contribuciones**

Las contribuciones son bienvenidas.  
Para contribuir:

1.  Haz un fork del repositorio
    
2.  Crea una rama con tu mejora
    
3.  Realiza commits siguiendo **Conventional Commits**
    
4.  Envía un Pull Request
