# Main build project

Composing both frontend and backend parts to launch them.

For developing with volume mounting:

```
docker-compose build
docker-compose up
```

For deploying:

```
docker-compose -f docker-compose.prod.yml build
docker-compose -f docker-compose.prod.yml up -d
```