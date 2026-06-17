# Parcial 2 - Software

**Nombre y Apellido:** Gabriel Gallardo 
**Fecha del parcial:** 17/06/2026  
**Descripción:** Proyecto  para el parcial 2 de la materia Ingeniería de Software. Consistirá en una página HTML >> nginx >> Docker.

## Cómo correr el proyecto

### Requisitos
- Tener [Docker](https://www.docker.com/) instalado

### Pasos

1. Clonar el repositorio:
```bash
   git clone https://github.com/gabrielgallardo83/parcial2.git
```

2. Entrar a la carpeta:
```bash
   cd parcial2-software
```

3. Construir la imagen:
```bash
   docker build -t parcial2 .
```

4. Correr el contenedor:
```bash
   docker run -p 8080:80 parcial2
```

5. Abrir en el navegador:
```
   http://localhost:8080
```