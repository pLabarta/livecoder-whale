# livecoder-whale
Dockerfiles for hosting livecoding services!
Dockerfiles para hostear servicios livecoderxs!

# Instrucciones

1. Instalar [docker](https://docs.docker.com/get-docker/)
2. `git clone https://github.com/pLabarta/livecoder-whale/`
3. Ingresar a la carpeta `cd livecoder-whale`
4. Crear la imagen con docker `docker build -t {NOMBRE_DEL_SERVICIO} {CARPETA DEL SERVICIO}`
  Ejemplo: `docker build -t cajita-hydra hydra-box`
5. Correr la imagen en la compu y conectar los puertos `docker run -p {PUERTO_COMPU}:{PUERTO_SERVICIO} {NOMBRE_DEL_SERVICIO`
  Ejemplo: `docker run -p 33331:8000 cajita-hydra`
6. Entrar al servicio usando el puerto que pusimos, en el caso de nuestra cajita-hydra seria entrar a https://localhost:33331 en cualquier browser
7. Livecodear
