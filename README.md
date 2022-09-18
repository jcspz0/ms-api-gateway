# Api gateway realizado en krakend

Api gateway para la actividad 1

# users

Para obtener todos los usuarios
`{host:port}/api/users`
\n
Para obtener los datos de un usuario
`{host:port}/api/users/{id}`

# posts

Para obtener todos los usuarios
`{host:port}/api/posts`
\n
Para obtener los datos de un usuario
`{host:port}/api/posts/{id}`

# user-posts

Para obtener los posts de un usuario
`{host:port}/api/user-posts/{id}`

# Pasos para levantar la web de reserva

Para levantar el gateway se debe de ir a la ubicación del archivo de configuración y ejecutar el siguiente comando

`docker run --name krakend -d -p "4444:4444" -v ${pwd}:/etc/krakend/ devopsfaith/krakend:2.0.5 run -c /etc/krakend/krakend.json `
