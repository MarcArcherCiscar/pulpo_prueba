# pulpo

Configuracion Laravel/BBDD
Primero debemos configurar el .env para que apunte a la bbdd que queramos.
luego lo que tenemos que hacer es levantar la bbdd con 'php artisan migrate'
Tambíen tengo hecho un seeder para que rellene de forma automatica algunos servicios, si queremos utilizarlo deberemos poner en el terminal 'php artisan db:seed'
Y luego ya solo nos quedaria levantar el servicio con 'php artisan serve'
Configuracion Ionic
Lo unico que tenemos que hacer aqui es iniciar el servicio(o crear una apk...) con 'ionic serve'

/* si da error por el sweetalert2 */
se tiene que poner esto en la terminal
npm install sweetalert2
