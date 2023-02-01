# Vallée du Gier

Create a docker of the [Vallée du Gier project](https://github.com/VCityTeam/UD-Demo-TIGA-Vallee-Du-Gier).  
_See the [online version]()_.

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo

```bash
git clone https://github.com/VCityTeam/UD-Demo-TIGA-Vallee-Du-Gier-docker.git
cd UD-Demo-TIGA-Vallee-Du-Gier-docker
```

Build the docker image with

```bash
docker build -t demo_vdg .
```

and run the container with

```bash
docker run -p 8001:80/tcp -t demo_vdg
```

and open a web browser on URL `http://localhost:8001/`
