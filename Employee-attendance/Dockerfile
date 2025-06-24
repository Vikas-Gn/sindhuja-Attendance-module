# Use nginx base image to serve static files
FROM nginx:alpine

# Copy app files (assumes build already done or static files exist)
COPY . /usr/share/nginx/html

# Expose port
EXPOSE 80

