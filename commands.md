Create Ixo github Docker Image (replace version with wanted version):

```bash
docker build -t ghcr.io/ixofoundation/flowise:v0.0.1 -f Dockerfile .
```

Push Ixo Docker Image to Ixo repo:

```bash
docker push ghcr.io/ixofoundation/flowise:v0.0.1
```
