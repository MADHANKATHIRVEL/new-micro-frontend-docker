# Use an official Nginx image as a base
FROM nginx:alpine

# Copy the HTML and CSS files to the Nginx directory
COPY index.html /usr/share/nginx/html/index.html
COPY styles.css /usr/share/nginx/html/styles.css

# Expose port 80 for the container
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
