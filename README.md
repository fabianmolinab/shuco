#Shusco
## Template the Next with Docker

## Features

- Typescript
- Eslint
- Prettier
- Jest(Test)
- Docker
- Husky

## Requirements

- Node +16v
- Docker
- Text Editor

## Install Dependencies

`yarn -i`

## Generating and running the container

1. `yarn -i`
2. `docker build -t [nombre-de-la-imagen]:[tag] .`
3. `docker run --name=[nombre-del-contenedor] -p 3030:3000 [nombre-de-la-imagen]`
