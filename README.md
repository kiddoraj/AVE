# AVE

AVE is a Python-based automated credit sales program designed to facilitate the management of credit sales for convenient goods such as sugar, flour, bread, etc. The program allows customers to purchase goods on credit terms, enabling them to defer payment until a later date with affordable interest rates on the principle. This initiative aims to leverage customer flexibility, drive sales revenue, and foster long-term customer relationships.

## Features

- Customer management system: Manage customer information and credit transactions.
- Credit calculation module: Calculate interest rates based on principles and terms.
- RESTful API: Expose endpoints for interacting with the credit sales program.
- Database integration: Store customer data and transaction information securely.
- Documentation: Generate API documentation using Swagger/OpenAPI.

## Technology Stack

- Programming Language: Python
- Dependency Management: Poetry
- Web Framework: Flask
- Database: SQLite (for development/testing), PostgreSQL (for production)
- ORM: SQLAlchemy
- API Documentation: Swagger/OpenAPI
- Version Control: Git/GitHub
- Deployment: Docker, Kubernetes (optional for scalability)

## Development Team

- Developer 1: [Name]
- Developer 2: [Name]
- Developer 3: [Name]
- Business Analyst: [Name]

## Getting Started

To get started with AVE, follow these steps:

1. Clone this repository to your local machine.
2. Install Poetry for dependency management (if not already installed).
3. Set up a virtual environment using Poetry.
4. Install dependencies by running `poetry install`.
5. Set up database (SQLite for development/testing, PostgreSQL for production).
6. Configure environment variables (if applicable).
7. Run the Flask application using `poetry run flask run`.
8. Access the API documentation at `http://localhost:5000/docs`.

## Contributing

Contributions to AVE are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) if you'd like to contribute.

## License

This project is licensed under the [MIT License](LICENSE).
