# practica-fetch


Este programa demuestra el aprendizaje del uso y dominio del lenguaje JavaScript para la generar archivos a traves de API REST, con el uso de servidores de JSON.

El objetivo de este proyecto, fue crear un CRM simple, en el que se evidenciara el control de los clientes atendidos por una agencia generica, y pudiera cumplirse desde el punto de vista de programación con un CRUD dentro dentro de os archivos. 

Se realizó un Front End ajustado a un control de clientes atendidos con datos basicos, como nombre, correo electronico, telefono y empresa en la que fueron atendidos. Se utilizó como Backend el uso de un API, creando un servidor simulado.

La estrategia del proyecto consistió en crear e archivos en Javascript de forma modular para la consolidacion de importacion y exportacion de informacion dentro de un mismo programa, la creacion de una API para poder ser consumida por los metodos GET, POST, DELETE y PUT, a fin de simular un API comercial para cargar los datos, y tomar estos datos y luego pudieran ser editados.

Fue instalado Node, npm, y se utilizó el paquete de json-server, asignando el puerto de 4000 para localhost. Por lo tanto para la prueba, es necesario contar con Node y npm en las versiones mas recientes e instalar json-server, a fin que pudiera ser utilizada la url que aparece en el archivo. el archivo de la base de datos es db.json.