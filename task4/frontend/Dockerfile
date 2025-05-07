# Use the official Nginx image
FROM nginx:latest

# Copy the front-end files into the Nginx web directory
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy custom Nginx config to override the default
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf