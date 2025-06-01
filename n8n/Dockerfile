# ┌──────────────────────────────────────────┐
# │  n8n/Dockerfile                         │
# └──────────────────────────────────────────┘
FROM n8nio/n8n:latest

# Entorno: la imagen oficial de n8n ya trae Node, etc.
# Solo necesitamos asegurarnos de que n8n use PostgreSQL externo.

# Definir working dir (aunque la imagen ya lo hace por defecto)
WORKDIR /home/node/

# Copiamos, si tuvieras archivos de workflow prediseñados, por ejemplo:
# COPY ./workflows/ /home/node/workflows/

# Exponer el puerto en el que n8n escuchará (por defecto 5678)
EXPOSE 5678

# No es necesario CMD porque la imagen oficial ya arranca n8n