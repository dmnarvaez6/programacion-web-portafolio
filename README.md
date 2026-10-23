# Portafolio Personal - Daniela Narváez

## Objetivo del proyecto

Desarrollar un sitio web personal utilizando HTML5 semántico y CSS para presentar información académica, intereses personales, recursos de aprendizaje y una galería fotográfica.

## Tecnologías utilizadas

- HTML5
- CSS3
- Docker
- Nginx
- Git
- GitHub
- Docker Hub

## Estructura del proyecto

```text
Mi-perfil/
│
├── Dockerfile
├── index.html
├── galeria.html
├── style.css
├── README.md
│
└── imagenes/
    ├── perfil.jpeg
    ├── foto1.jpeg
    ├── foto3.jpeg
    ├── foto4.jpeg
    ├── foto5.jpeg
    ├── foto6.jpeg
    ├── foto7.jpeg
    ├── foto8.jpeg
    └── foto10.jpeg
```

## Construcción de la imagen Docker

Ubicarse en la carpeta del proyecto:

```bash
cd Mi-perfil
```

Construir la imagen:

```bash
docker build -t mi-perfil-html .
```

## Ejecución del contenedor Docker

Ejecutar el contenedor:

```bash
docker run -d -p 8082:80 --name portafolio-daniela mi-perfil-html
```

Abrir en el navegador:

```text
http://localhost:8082/index.html
```

## Enlace a Docker Hub

Repositorio Docker Hub:

```text
https://hub.docker.com/r/nani2516/mi-perfil-html
```

## Autor

Daniela Mabel Narváez Suntaxi

Ingeniería en Software
Universidad de las Fuerzas Armadas ESPE
