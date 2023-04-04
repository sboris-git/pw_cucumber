# pw_cucumber
sandbox for playwright cucumber simple framework

project/
│
├── features/
│   ├── gmail_login.feature
│   └── steps/
│       ├── __init__.py
│       └── login_steps.py
│
├── pages/
│   ├── __init__.py
│   └── LoginPage.py
│
├── dao/
│   ├── __init__.py
│   └── UserDao.py
│
├── dto/
│   ├── __init__.py
│   └── UserDto.py
│
├── config.py
├── requirements.txt
└── env
    ├── dev.env
    ├── staging.env
    └── prod.env

Here's a brief description of the folders and files in the project:

features/: This folder contains your feature files written in Gherkin syntax. It also contains the step definitions for those feature files.
pages/: This folder contains your page objects. Each page object represents a web page or a section of a web page and provides an API for interacting with the page.
dao/: This folder contains your data access objects (DAOs). DAOs provide an abstraction layer between your application code and the database, making it easier to read and write data.
dto/: This folder contains your data transfer objects (DTOs). DTOs are used to transfer data between different layers of your application.
config.py: This file contains your application configuration. You can define settings such as the browser type, the launch options, and the URLs for different environments.
requirements.txt: This file lists the required Python packages for your project.
env/: This folder contains environment-specific configuration files. You can define different environment variables for your dev, staging, and prod environments in separate .env files.
