PARA VERLO EN LOCAL</br>

1.- Instalar node.js, npm incluido</br>
2.- Crear un directorio	(p.e. documentos/romcal)</br>
	2.1 .- Ejecutar npm init (pide metadatos del proyecto)</br>
3.- Del código fuente del proyecto, copiar los directorios</br> 
		html-web-page</br>
		react-app</br>
		rest-api-with-express</br>
		rest-api-with-fastify</br>

4.- Arrancar una consola DOS en cada directorio</br>
5.- Ejecutar:</br>

	npm install romcal@dev</br>
	npm install @romcal/calendar.france@dev</br>
	npm install @romcal/calendar.spain@dev</br>
		
	esto crea los directorios @romcal con los calendarios solicitados</br>
6.- Los package.json llevan los comandos y las actualizaciones.</br>
7.- Con npm start, se inicia y se visualia en el puerto que indique</br>	

PARA VERLO EN UN SERVIDOR DE INTERNET</br>

Se requiere: </br>
  node.js (NPM instalación de paquetes)</br>
  NGnix (PM2 convierte a servicio daemon)</br>
  Para más info:</br>
  Cómo configurar una aplicación de Node.js para producción en Ubuntu 18.04 | DigitalOcean</br>
  https://www.digitalocean.com/community/tutorials/como-configurar-una-aplicacion-de-node-js-para-produccion-en-ubuntu-18-04-es</br>
