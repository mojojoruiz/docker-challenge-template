# Use the official Nginx image as the base
FROM nginx:latest

# Copy the public folder to the Nginx default directory
COPY public /usr/share/nginx/html

# Expose port 8080 to the outside world
EXPOSE 8080

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
