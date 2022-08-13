PARA VERLO EN LOCAL

1.- Instalar node.js, npm incluido
2.- Crear un directorio	(p.e. documentos/romcal)  
	2.1 .- Ejecutar npm init (pide metadatos del proyecto)
3.- Del código fuente del proyecto, copiar los directorios 
		html-web-page
		react-app
		rest-api-with-express
		rest-api-with-fastify

4.- Arrancar una consola DOS en cada directorio
5.- Ejecutar:

	npm install romcal@dev
	npm install @romcal/calendar.france@dev
	npm install @romcal/calendar.spain@dev
		
	esto crea los directorios @romcal con los calendarios solicitados
6.- Los package.json llevan los comandos y las actualizaciones.
7.- Con npm start, se inicia y se visualia en el puerto que indique	

PARA VERLO EN UN SERVIDOR DE INTERNET

Se requiere: 
  node.js (NPM instalación de paquetes)
  NGnix (PM2 convierte a servicio daemon)
