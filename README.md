# FILMFAV WEB 🍿 - Evaluativo JS (GMunicipalidad de Yerba Buena + Global Learning Tucumán) 📱💻

Este repositorio contiene el código perteneciente al _**evaluativo de conocimientos en JS, HTML y CSS**_ para la capacitación en conocimientos actualizados de REACT, proyecto de la Munincipalidad de Yerba Buena en conjunto con Global Learning Tucumán. Consiste en una web con interfaz responsive que simula ser _una plataforma de visualización y calificación de películas por parte de supuestos usuarios_.

## Consigna evaluativa 👀

En base a una **lista de usuarios y una lista de películas** vistas por dichos usuarios, realizar una función que permita **obtener un nuevo arreglo de objetos** en el cual cada objetos consta con el _nombre del usuario, su email, su dirección completa, su compañía, el título de la película vista y la calificación de la misma_. La función debe poseer un **filtro por fecha , por calificación y por id de usuario**. Si no se envía un userId , la función deberá _devolver todas las películas que cumplan las condiciones de los filtros_ de fecha y calificación para todos los usuarios existentes.

⚠️ Nombre de función y parámetros necesarios:

```http
filterMovies ( { users, movies, userId, fromDate, toDate, rate } );
```

⚠️ Cada objeto del arreglo debe tener la siguiente estructura:

```http
{
id : user.id,
username : user.username.
email : user.email,
fullAddress : `${user.address.street} - ${user.address.city}`
company : user.company.name,
movie : movie.title,
rate : movie.rate
}
```

## Instalación ✅

Este proyecto corre con **"Open with Live Server"** de Visual Code dado que está hecho con solamente **HTML, CSS y JS**.

## Sitio Web 💻

Este proyecto se encuentra deployado en:
[https://filmfav.netlify.app/](https://filmfav.netlify.app/)

## ¿Alguna duda o sugerencia? ❓

Por dudas o sugerencias, contactarse a lunama.cecilia@mail.com

## Autora 🖌️

- [Cecilia Luna 👩‍💻](https://github.com/MCeciliaLuna)

## Licencia 🤝

Este repositorio es _PÚBLICO_.

## Estado 📈

**EN CURSO**
