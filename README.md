# React app

## Construir la imagen

`docker build -t reactapp:16 .`

## Arrancamos en background (-d)
`docker run --rm --name miapp -d -p 3000:3000 reactapp:16`

## Parar el contenedor (y se borrará)

`docker stop miapp`