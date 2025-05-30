# Freelando Web API Course: Mastering EF Core Transactions with .NET 8

![Freelando Web API](https://img.shields.io/badge/Freelando_WebAPI-Entity_Framework_Core-007ACC?style=for-the-badge&logo=dotnet&logoColor=white)

Welcome to the **Freelando Web API Course** repository! This project contains exercises from the course “.NET: Avance na Persistência com EF Core” offered by Alura. The course focuses on advanced queries, rich models, transaction management, architectural best practices, and SQL command interception using Entity Framework Core.

## 🚀 Quick Start

To get started with the exercises, you can download the latest release from our [Releases page](https://github.com/marcin-kor/freelando_webapi_course-alura-entity-framework-core-transactions_part-11_dotnet-8_csharp-12/releases). Follow the instructions in the release notes to execute the project.

## 📚 Course Overview

This course is designed for developers looking to deepen their understanding of Entity Framework Core. Here’s what you will learn:

- **Advanced Queries**: Learn how to optimize your queries for better performance.
- **Rich Models**: Understand how to create and manage complex data models.
- **Transaction Management**: Master the use of transactions to ensure data integrity.
- **Architectural Best Practices**: Discover patterns that improve the maintainability of your code.
- **SQL Command Interception**: Learn how to intercept and modify SQL commands generated by EF Core.

## 🛠️ Technologies Used

This repository utilizes the following technologies:

- **C#**: The primary programming language for building .NET applications.
- **.NET 8**: The latest version of the .NET framework.
- **Entity Framework Core**: An object-relational mapper for .NET that allows developers to work with databases using .NET objects.
  
## 📂 Repository Structure

The repository is organized as follows:

```
/src
    /Freelando.WebAPI
        /Controllers
        /Models
        /Data
        /Services
    /Tests
        /Freelando.WebAPI.Tests
```

- **/src**: Contains the source code for the project.
- **/Freelando.WebAPI**: The main application folder.
- **/Controllers**: Contains the API controllers.
- **/Models**: Contains the data models used in the application.
- **/Data**: Contains the database context and migrations.
- **/Services**: Contains business logic and service classes.
- **/Tests**: Contains unit tests for the application.

## 🔧 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/marcin-kor/freelando_webapi_course-alura-entity-framework-core-transactions_part-11_dotnet-8_csharp-12.git
   cd freelando_webapi_course-alura-entity-framework-core-transactions_part-11_dotnet-8_csharp-12
   ```

2. **Install dependencies**:
   Ensure you have the latest version of .NET SDK installed. You can check your installation by running:
   ```bash
   dotnet --version
   ```

3. **Build the project**:
   ```bash
   dotnet build
   ```

4. **Run the application**:
   ```bash
   dotnet run --project src/Freelando.WebAPI/Freelando.WebAPI.csproj
   ```

5. **Access the API**:
   Open your browser and navigate to `http://localhost:5000/api`.

## 📝 Usage

After setting up the project, you can explore the various API endpoints. Use tools like Postman or curl to interact with the API. Here are some common operations you can perform:

- **Get all items**:
  ```http
  GET /api/items
  ```

- **Get a specific item**:
  ```http
  GET /api/items/{id}
  ```

- **Create a new item**:
  ```http
  POST /api/items
  ```

- **Update an item**:
  ```http
  PUT /api/items/{id}
  ```

- **Delete an item**:
  ```http
  DELETE /api/items/{id}
  ```

## 🔍 Topics Covered

This course covers several important topics:

- **alura**: The educational platform providing this course.
- **architecture**: Best practices in software architecture.
- **csharp**: The programming language used throughout the course.
- **dotnet**: The framework that supports building applications.
- **ef-core**: The core library for Entity Framework.
- **entity-framework**: The ORM that simplifies database interactions.
- **interception**: Techniques for intercepting SQL commands.
- **query-optimization**: Strategies for improving query performance.
- **rich-model**: Creating models that encapsulate business logic.
- **transactions**: Managing data changes safely and reliably.

## 📖 Learning Resources

To further enhance your understanding, consider exploring the following resources:

- [Official .NET Documentation](https://docs.microsoft.com/en-us/dotnet/)
- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)
- [Alura Course Page](https://www.alura.com.br/)

## 🛠️ Tools & Libraries

This project uses several tools and libraries to enhance development:

- **Visual Studio**: A powerful IDE for .NET development.
- **Postman**: A tool for testing APIs.
- **Entity Framework Core Tools**: Command-line tools for EF Core.

## 📦 Releases

For the latest updates and versions, please check our [Releases page](https://github.com/marcin-kor/freelando_webapi_course-alura-entity-framework-core-transactions_part-11_dotnet-8_csharp-12/releases). Make sure to download and execute the latest release to benefit from new features and fixes.

## 🤝 Contributing

We welcome contributions! If you have suggestions for improvements or new features, please open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📫 Contact

For questions or feedback, please reach out:

- GitHub: [marcin-kor](https://github.com/marcin-kor)
- Email: marcin.kor@example.com

Thank you for visiting the **Freelando Web API Course** repository! We hope you find the exercises valuable in your journey to mastering Entity Framework Core.