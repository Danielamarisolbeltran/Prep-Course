# Homework: Javascript IV

<Ej 2: funcion agregarPropiedad.>
Utilizamos brackets[]para q agregue una propiedad, sino con dot notation (.) solo la buscaria en el obj.

<Ej 3: invocarMetodo.>
Invocamos el metodo dentro del objeto, poniendo : [metodo], luego lo invocamos con las ()

<Ej 7 tieneEmail>: Dentro del obj estamos preguntando si la propiedad tiene un valor. Usando usuario.email.

<Ej 8: tienePropiedad>  
usando el metodo hasOwnProperty. Para averiguar si tenemos dicha propiedad dentro del objeto.

<Ej 9 verificarPassword>
<Ej 10 actualizarPassword >
<Ej 11 agregarAmigo>
<Ej 12 pasarUsuarioAPremium>
<Ej 13 sumarLikesDeUsuario>
Recorremos el array con for, para poder acceder a cada objeto, y a la prop likes dentro de cada uno.
objeto -User>
propiedad -posts(que es un array de objetos)
recorremos cada objeto, y buscamos la propiedad -Likes en cada uno.

<Ej 14 agregarMetodoCalculoDescuento>
Usamos la palabra reservada 'this' haciendo referencia al contexto donde se ejecuta el metodo. Una forma de referirnos al objeto. En este caso objeto producto.


## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos
	* Propiedades
	* Métodos
	* Bucle `for…in`
	* Notación de puntos vs notación de corchetes

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSIV.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/05-JS-IV/homework/homework.js)