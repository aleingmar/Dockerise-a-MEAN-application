# Imagen base
FROM nginx:stable

# Eliminar configuración por defecto
RUN rm /etc/nginx/conf.d/default.conf

# Copiar nuestro nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf