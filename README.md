# Vue ChatGPT

Simple interface para probar ChatGPT.

![image](https://user-images.githubusercontent.com/108734/224945519-7cc1e3aa-5146-4f8a-8b2e-d46a9a2bb5ae.png)

## Tecnología

- VueJS

Puedes encontrar una versión con ExpressJS en el backend: https://github.com/akobashikawa/express-chatgpt

## Instalación

- Clonar el repositorio y publicarlo con algún servicio http
- `live-server`
- http://localhost:8080
- Ingresa en la configuración el *apiKey* obtenido en tu cuenta OpenAI
- También se puede indicar en el apiKey en el url:
    - http://localhost:8080/?apiKey=secret

## Demo
- https://akobashikawa.github.io/vue-chatgpt
- El markdown devuelto por ChatGPT es convertido a HTML.
- Se hace highlight de los bloques `code`.
