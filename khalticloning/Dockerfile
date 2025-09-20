# # Use an official Nginx image as a base
# FROM nginx:alpine

# # Remove the default Nginx configuration
# RUN rm /etc/nginx/conf.d/default.conf

# # Copy your custom Nginx configuration
# COPY nginx.conf /etc/nginx/conf.d/

# # Copy all your project files into the Nginx web root
# # The '.' copies everything from the current build context (your project root)
# # to '/usr/share/nginx/html' inside the container.
# COPY . /usr/share/nginx/html

# # Expose port 80 (the default HTTP port)
# EXPOSE 80

# # Start Nginx when the container launches
# CMD ["nginx", "-g", "daemon off;"]

FROM nginx:alpine
COPY . /usr/share/nginx/html/
EXPOSE 80
