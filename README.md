# 🌟 api-crud-beautique - Simple API for CRUD Operations

## 🛠️ Overview

**api-crud-beautique** is a straightforward API designed to manage CRUD (Create, Read, Update, Delete) operations. You can use this API to interact with your database easily. Whether you want to store information, retrieve it, update it, or delete it, this API covers your needs effectively.

## 📥 Download

[![Download the latest release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)](https://github.com/SBSMSG/api-crud-beautique/releases)

## 🚀 Getting Started

Follow these steps to download and run **api-crud-beautique**.

### 🔍 System Requirements

- **Operating System:** Windows, Mac, or Linux
- **Java Version:** You need Java 17 installed on your machine.
- **Memory:** At least 512 MB of RAM.
- **Storage:** Minimum of 100 MB free disk space.

### 📋 Features

- Perform CRUD operations easily.
- Supports both MongoDB and PostgreSQL databases.
- Quick API responses with RabbitMQ integration.
- Uses Maven for dependency management.

## 📦 Download & Install

1. Visit the [Releases page](https://github.com/SBSMSG/api-crud-beautique/releases) to download the latest version.
   
2. Select the release that fits your operating system. 

3. Download the file. 

4. Once downloaded, locate the file on your computer.

5. Open your terminal or command prompt.

6. Navigate to the folder where you downloaded the file.

7. Run the following command:

   ```
   java -jar <name-of-the-downloaded-file>.jar
   ```

8. Your API should now be running. You can access it via your web browser or Postman.

## 🔧 Configuration

To connect the API to your database:

1. Open the `application.properties` file in your text editor.
2. Modify the following settings:

   ```properties
   spring.datasource.url=jdbc:postgresql://<your-postgres-url>:5432/your-database
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   ```

3. For MongoDB, adjust the URL accordingly.

## 📈 Usage

With **api-crud-beautique**, you can make HTTP requests to perform various operations:

- **Create**: Send a POST request to `/api/resource` with the data to create.
  
- **Read**: Send a GET request to `/api/resource` to retrieve data.

- **Update**: Use a PUT request to `/api/resource/{id}` with the updated data.

- **Delete**: Send a DELETE request to `/api/resource/{id}` to remove data.

## ✨ Support

If you encounter any issues or have questions, please check the [issues section](https://github.com/SBSMSG/api-crud-beautique/issues) on GitHub. You can also submit your questions there for further assistance.

## 📚 Additional Resources

For more information:

- [Java Documentation](https://docs.oracle.com/en/java/)
- [Maven Documentation](https://maven.apache.org/guides/)
- [Spring Framework Guide](https://spring.io/guides)

## 🎉 Acknowledgements

This project uses several libraries, including:

- **Spring Web** for building web applications.
- **Flyway** for database versioning.
- **Model Mapper** for mapping objects.
- **FasterXML** for JSON processing.

Thank you for your interest in **api-crud-beautique**! We hope this helps you manage your CRUD operations with ease.