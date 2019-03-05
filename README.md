# Taller-ORM
Taller implementación de un ORM Desarrollo II

Para probar las operaciones CRUD abrir Postman y seguir los pasos documentados aqui.

1. Consultar: 

Para consultar los contactos solo se ingresa la url http://node10.codenvy.io:42234/contacts con el método GET.

2. Crear: 

Para crear vamos sobre la misma url http://node10.codenvy.io:42234/contacts con el metodo POST y modificamos el body 
para ingresar un nuevo usuario:

{
  "firstName": "test",
  "lastName": "numero uno",
  "emailAdress": "test@test.com"
}


3. Editar:

Para editar vamos sobre la url http://node10.codenvy.io:42234/contacts/{id} con el método PUT y se le
agrega el id del contacto que se quiere editar y se cambia la información en la sección body asi:

{
  "firstName": "test editado",
  "lastName": "numero uno editado",
  "emailAdress": "test2@test.com"
}

4. Eliminar:

Para eliminar vamos sobre la url http://node10.codenvy.io:42234/contacts/{id} con el método
DELETE y se le agrega el id del contacto que se quiere eliminar
