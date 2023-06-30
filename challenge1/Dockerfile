FROM wordpress:latest

# Install MySQL client
RUN apt-get update \
    && apt-get install -y mysql-client \
    && rm -rf /var/lib/apt/lists/*

# Copy custom theme
COPY mytheme /var/www/html/wp-content/themes/mytheme

# Set environment variables
ENV WORDPRESS_DB_HOST=mysql \
    WORDPRESS_DB_USER=root \
    WORDPRESS_DB_PASSWORD=password \
    WORDPRESS_DB_NAME=mydatabase

# Expose port 80
EXPOSE 80