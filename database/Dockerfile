# Use the official MySQL image from the Docker Hub
FROM mysql:8.0

# Set environment variables for the MySQL root password, database name, and user
ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=my_database
ENV MYSQL_USER=my_user
ENV MYSQL_PASSWORD=my_password

# Expose the default MySQL port
EXPOSE 3306

# Add a custom SQL script if you need to initialize the database with some data
COPY ./init.sql /docker-entrypoint-initdb.d/

# Command to run MySQL server
CMD ["mysqld"]
