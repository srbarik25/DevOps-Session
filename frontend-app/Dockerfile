# Use the official Nginx image as the base image
FROM nginx:1.23-alpine

# Copy the custom Nginx configuration file (optional)
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the static website files
# COPY html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]