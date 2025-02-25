# Use Nginx as base image
FROM nginx:latest

# Remove default Nginx page and add custom HTML
RUN rm -rf /usr/share/nginx/html/*
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
