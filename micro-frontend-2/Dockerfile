# Use an official Nginx image as a base
FROM nginx:alpine

# Copy the HTML and JS files to the Nginx directory
COPY index.html /usr/share/nginx/html/index.html
COPY script.js /usr/share/nginx/html/script.js

# Expose port 80 for the container
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
