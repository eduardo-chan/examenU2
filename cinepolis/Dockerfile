
# Copiar los archivos compilados desde la etapa de construcción a la carpeta de Nginx
COPY --from=build /app/dist /usr/share/nginx/html

# Copiar configuración de Nginx (si necesitas personalizarla)
# Puedes crear un archivo personalizado de configuración en tu proyecto y copiarlo aquí
# COPY nginx.conf /etc/nginx/nginx.conf

# Exponer el puerto de Nginx
EXPOSE 80

# Comando de inicio de Nginx
CMD ["nginx", "-g", "daemon off;"]
