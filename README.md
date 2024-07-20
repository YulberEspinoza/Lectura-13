# Lectura-13

1. ¿Por qué un desarrollador utilizaría el local storage para una aplicación web?
Nuestro desarrollo utiliza nuestro local o nuestra maquina para poder almacenar nuestros datos, esto nos ayuda a que cuando estamos trabajando y no queremos que nuestros datos se pierdan utilizamos el local storage, se quedan los datos y mas adelante podemos darle un tratamiento. 

2. ¿Qué información no se puede guardar en el local storage?
Este tratamiento de datos es muy sensible a ciertos datos, como: objetos, numeros, contraseñas y otros. También los archivos que necesitan varios recursos, los cuales al estar sujetos a muchos dispositivos y que tengan una sincronización externa.

3. ¿Qué tipo de datos se pueden guardar en el local storage? ¿Cómo puedes convertirlo a ese tipo de archivo antes de guardarlo?
Local storage solo puede guardar algunos datos y sin tener problemas para reconocerlo, tenemos el tipo de dato "string"; que es una cadena de texto y podemos realizar un tratamiendo de datos. Podemos convertir cualquier tipo de dato con JSON.stringify y lo guardamos en el local storage y con localstorage.setItem; podemos permitir mostrarlos.
