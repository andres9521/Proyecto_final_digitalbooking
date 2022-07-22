# Proyecto_final_digitalbooking
En este proyecto la lógica de la aplicación (Backend) fue desarrollada con Java, incluyendo Spring para la creación del patron de diseño MVC como guía principal para la creación de una REST API y haciendo uso de un ORM (Hibernate) para interactuar con la base de datos, la cual se desarrollo en Mysql.

## Indice
* [El Proyecto](#proyecto)
* [Metodología de Trabajo](#metodología-de-trabajo)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Documentación Técnica del Proyecto](#documentación-técnica-del-proyecto)



## El proyecto
Digital booking es un sitio web que nos permite realizar reservas de alojamientos categorizados en hoteles, hostels, departamentos y bed & breakfast en distintos lugares turísticos del mundo.
El sitio puede ser utilizado por usuarios para buscar alojamientos y realizar reservas, y también por administradores, que además pueden publicar sus productos.

Nuestro objetivo es desarrollar un producto digital acorde a las funcionalidades requeridas por el cliente. Nuestra prioridad era lograr que sea responsivo, intuitivo y fácilmente de entender, para que los usuarios tengan una buena experiencia y vuelvan a visitarlo.
<br>

---

<summary><em>Andres Robledo</em></summary>

<br>
Conocimientos al iniciar la carrera:
<ul>
<li>HTML Básico</li>
</ul>

<blockquote>
<h5>Rol:</h5>
<ul>
<li>Bases de datos</li>
<li>Backend</li>
<li>Testeo de APIs</li>
</ul>
</blockquote>
<blockquote>
<h5>Tareas: </h5>
<ul>
<li>Armado de estructura de tablas de la base de datos</li>
<li>Armado de estructura del proyecto bajo el patrón MVC usando Sping</li>
<li>Creación y actualización de los respository, service y controller</li>
<li>Realización de script de tests en Postman para comprobar el funcionamiento de los endpoint según los requerimientos</li>
</ul>
</blockquote>

| Tecnología | Fortaleza |
| ------ | ------ |
| Front end | 🔵 🔘 🔘 |
| Back end | 🔵 🔵 🔘 |
| Infraestructura | 🔵 🔘 🔘 |
| Testing / QA | 🔵 🔘 🔘 |
| Base de Datos | 🔵 🔵 🔘 |


---

[<div align= "right"><img src="uploads/6f060f0408bc0475855bb4a7d9cd88da/flecha.png" width="20"></div>](#indice)

## Metodología de trabajo

Trabajamos con Metodologías Ágiles. Para ello nos organizamos siguiendo las ceremonias de SCRUM (lectura y validación del sprint, daily, weekly, review, retro), modularizando el proyecto en 4 Sprints de 2 semanas cada uno.<br>
A lo largo del proyecto contamos con un Scrum Master, un Product Owner y el apoyo de diferentes Tech Leads en caso que necesitáramos realizar consultas técnicas. Utilizamos el Boards de GitLab como herramienta de organización y asignación de tareas y Metro Retro para asegurarnos de mejorar como equipo de manera progresiva para asi lograr los objetivos. 
Desde el comienzo del proyecto nos dividimos de manera clara los roles pero también establecimos solucionar en grupo aquellas dudas y features más complejas a resolver a lo largo del desarrollo.

[<div align= "right"><img src="uploads/6f060f0408bc0475855bb4a7d9cd88da/flecha.png" width="20"></div>](#indice)


## Tecnologías Utilizadas
<ul>

<li>Servicios & herramientas empleadas:
<ul>
<li>Gestión del proyecto: 
<ul> 
<li>GitLab Boards</li>  
<li>Gitlab Issues</li>  
<li>Metro Retro</li>
</ul>

</li>
<li>Desarrollo del proyecto: 
<ul> 
<li>IDEs
<ul> 
<li>Visual Studio Code</li>  
<li>IntelliJ</li>  
</ul>
</li>  
<li>Sistemas de Control de Versiones
<ul> 
<li>Git</li>
<li>Gitlab</li>  
</ul></li>  
</ul>
</ul>
</li>

<li>Tecnologías Utilizadas:
<ul> 
<li>Frontend
<ul> 
<li>Javascript</li>  
<li>React</li>   
</ul>
</li>  
<li>Backend
<ul> 
<li>Java</li>  
<li>Spring</li>  
<li>Swagger</li>
<li>Hibernate</li> 
</ul>
</li>  
<li>Base de Datos
<ul> 
<li>MySQL</li>  
<li>MySQLWorkbench</li>
<li>DBeaber</li>  
</ul></li>  
<li>Testing
<ul> 
<li>Jest</li>  
<li>SeleniumIDE</li>  
<li>Postman</li>  
</ul></li>  
<li>Infraestructura
<ul>
<li> AWS
<ul>  
<li>S3</li>  
<li>EC2</li>  
<li>RDS</li>  
</ul>
</li>  
</ul>
</li> 
</ul>
</li>
</ul>

[<div align= "right"><img src="uploads/6f060f0408bc0475855bb4a7d9cd88da/flecha.png" width="20"></div>](#indice)
---
## Documentación Técnica del Proyecto

### Ambiente de Desarrollo

- **Setup**

Para comenzar a trabajar, clonar el repositorio de Gitlab: 

Con SSH: 
```
$ git clone git@gl.deitech.online:ctd/proyecto-integrador-0522/0821-c1/grupo-03.git
```

Con HTTPS: 
```
$ git clone https://gl.deitech.online/ctd/proyecto-integrador-0522/0821-c1/grupo-03.git
```

Para correr el proyecto, instale localmente las siguientes librerías:

```
$ npm install
$ npm start
```

- **Workflow**
<br>
<p>El proyecto se lleva a cabo en la rama "development". De ella se desprenden ramas con cada feature que se desarrolla (las mismas están detalladas en el board de "Issues"). Una vez realizada la feature, se mergea con la rama development haciendo un Pull Request (incluyendo un mensaje descriptivo sobre el contenido del pull request)</p>

---

###  Testing

##### Casos de Prueba

 ▫ [Link a Casos de Prueba](https://docs.google.com/spreadsheets/d/1bfJzKTFHmY1OdETJ3Pa8pM62OVbm7vrM/edit#gid=78607399) 
<br>

##### Casos de Prueba

 ▫ [Link a Reporte final de testing](https://docs.google.com/document/d/1SfuRLzVw7AcsZ58fu3UfNwrcbvtcCz8z/edit?usp=sharing&ouid=107403431941075889636&rtpof=true&sd=true) 
<br>

##### Postman (Tests de API de Categorías)
![categoria](https://user-images.githubusercontent.com/82002822/180569757-7ac2ffd5-0dca-4ff8-935c-b6eece072064.png)

<br>

---


[<div align= "right"><img src="uploads/6f060f0408bc0475855bb4a7d9cd88da/flecha.png" width="20"></div>](#indice)

---




##### Jest

![jest](https://user-images.githubusercontent.com/82002822/180570025-94c7dc9e-b5c2-4500-bf6d-360306e9733a.png)


##### Postman (Tests de APIs de Productos y Ciudades)

![productypolicy](https://user-images.githubusercontent.com/82002822/180570060-5376ab6b-94dc-433b-b601-5cc9d4ff2fc0.png)

![city](https://user-images.githubusercontent.com/82002822/180570069-a2e74de7-5bb5-46c2-8f5e-ed7d76e46c35.png)

##### Postman (Tests de APIs de reservation)

![reservation](https://user-images.githubusercontent.com/82002822/180572161-2a09d38f-6d7c-4684-99cf-ab36875e2fc7.png)

##### Postman (Tests de APIs de user)

![user](https://user-images.githubusercontent.com/82002822/180572214-1e1bc381-78ee-40d0-b76d-058bb4154201.png)


[<div align= "right"><img src="uploads/6f060f0408bc0475855bb4a7d9cd88da/flecha.png" width="20"></div>](#indice)

---

### Base de Datos
##### Diagrama Entidad-Relación de digitalbooking

![Sprint3](https://user-images.githubusercontent.com/82002822/180570153-15058cde-10f4-41c5-8eba-bd2aecfeee68.png)


<br>


---
