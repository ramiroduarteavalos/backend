## Descripción
Simple backend para DevOps test.

## Docker
```bash
git clone git@github.com:ramiroduarteavalos/backend.git
cd backend
docker login
docker build -t ramiroduarteavalos/backend:1.0 .
docker push ramiroduarteavalos/backend:1.0
```

### Run
Este proyecto requiere Docker instalado en tu sistema.

## Endpoints
Contiene un solo endpoint `/welcome` que responde la fecha/hora del servidor.
