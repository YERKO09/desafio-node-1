# Veterinaria JS 
    Desafío 1, Introducción a Node.

## Detalles
* APP hecha en **ES6**.

* Para usar los módulos se debe crear el package.json con el siguiente comando:
```crear package.json
npm init -y 
```

* Luego en las dependecias se debe agregar la siguiente línea:
```importar módulos
"type": "module"
```

* De esta manera estará disponible para su uso **IMPORT** y **EXPORT**

* Con CommonJS también se puede hacer uso de estas palabras claves en lugar del '**require**' por ejemplo, pero se debe cambiar la extensión del archivo de script.js a script.mjs. Con esto evitamos tener que inicializar npm y configurar el package.json

## Instrucciones de uso de la app
* La app cuenta con las dos funciones principales creadas en el **operaciones.js**:
    * __leerCitas()__ para leer las citas registradas en el archivo **citas.json**
    * __crearCita()__ para insertar datos de una nueva mascota a la lista 

* ### Ejecutar en consola:
    * para crear una nueva cita usamos el siguiente comando en la terminal, ejemplos: <br>
    <code>node index.js crearCita Alfi "4 meses" "Gato Romano" Blanco Sanito</code><br>
    <code>node index.js crearCita Rabito "11 años" "Perro Mestizo" Beige Sanito</code><br>
    <code>node index.js crearCita Sami "1 año y 4 meses" "Perra Pitbull" Café Sanita</code>
    * ahora que tenemos **citas.json** con diferentes datos usamos la función **leerCitas()**, ejemplo: <br>
    <code>node index.js leerCitas</code><br>
        Como resultado veremos una tabla con los datos insertados ya que en lugar de console.log usé console.table 


