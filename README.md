Amigo-Secreto | Funcionalidades d
📝 Funcional
Comienza declarando un array destinado a guardar los nombres de los participantes que se vayan ingresando.

Ejemplo:

js

Copiar código
let amigos = [];
➕ Funcionalidad 2
Desarrolla una función que permita a los usuarios ingresar nombres a través de un campo de texto y sumarlos a la lista previamente cre

Pasos a seguir:
1️⃣ Capturar el valor ingresado : Utiliza `docudocument.getElementByIdo `document.querySelectordocument.querySelectorpara obtener el nombre introducido

2️⃣ Validar la entrada : Antes de agregarlo a la lista, verifica que el ca"Por favor, inserte un nombre."

3️⃣ Actualizar el array : Si la entrada es vamigoscon el método .push().

4️⃣ Limpiar el campo de texto : Luego de a

🔄 Función
Crea una función que graba el array amigosy genere<li>dentro de una estructura

Pasos a seguir:
1️⃣ Seleccionar el elemento de la lista : Estados Unidosdocument.getElementByIdo `documentdocument.querySelectorpara obtener la referencia

2️⃣ Limpiar la lista antes de actualizar : Establece lista.innerHTML = ""para

3️⃣ Recorrer el array : Mediantfor, genera un elemento<li>Para cada amigo en la lista.

4️⃣ Añadir los elementos al DOM :

🎲 Funcionalidad 4 | Sorteo al
Crea una función que selecciona al azar un nombre dentro del array amigosutilizando Math.random()y `MatMath.floor().

Pasos a seguir:
1️⃣ Verifica la disponibilidad de nombres : Antes de realizar el sorteo, asegúrate de que el array no esté vacío.

2️⃣ Generar un índice aleatorio: Usa Math.random()y Math.floor()para obtener una posición a

3️⃣ Obtener y mostrar el nombre sorteado : Extrae el nombre correspondiente al índocument.getElementById().innerHTML.
