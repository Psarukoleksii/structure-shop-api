# General structure for web-shop

## Assets
This folder contains static files like images, fonts, and downloadable files that are served directly by the application

## Configs
Holds configuration files or modules that manage the application's settings and environment variables. This can include database configurations, API keys, and other environment-dependent settings that help decouple configuration from business logic, facilitating easier updates and maintenance.

## Contexts
This directory is less common by default but might be used in larger applications for context-specific configuration or logic, like handling multi-tenancy or separating parts of the application into distinct areas with their own specific configurations and services.

## Decorators
Contains custom decorators that extend the functionality of classes, methods, or properties. Decorators in NestJS are often used for adding metadata to classes easily, which can be utilized for custom routing, class serialization, validation, and more.

## Environments
This folder typically includes files for different deployment environments, such as development, staging, and production. Each file contains environment-specific variables which help in setting up the application appropriately depending on where it is deployed.

## Guards
Includes classes that are responsible for determining whether a given request will proceed in the application's workflow. They are used in authorization strategies, such as validating user permissions before allowing access to certain functions or routes.

## Helpers
This directory is used for utility functions and classes that provide common functionality across various parts of the application. Helpers can include data formatting, custom logging functions, or other utility services that don't fit neatly into the framework's other abstractions.

## Interfaces
Contains TypeScript interfaces that define the structured data types used across the application. These are used to enforce type checking and ensure that data conforms to a specified format across classes and functions.

## Migrations
Stores migration scripts for databases. These scripts are used to handle changes to the database schema, allowing you to version control your database's structure and apply consistent updates across different environments.

## Models
Holds classes that define the structure of entity in DB.

## Modules
Consists of modules of entities that organize the application into discrete blocks of functionality. Each module encapsulates a related set of capabilities and can include controllers, services, and providers, making the application more modular and maintainable.

## Tests
Contains test scripts and configurations for testing the application. This includes unit tests, integration tests, and end-to-end tests, which are essential for ensuring the application functions correctly and continues to do so as changes are made.

## Utils
Similar to helpers, this directory includes utility functions or classes that are used across various components of the application. Utilities can include more complex functions or those that are used by many other components within the application, such as data transformation tools or custom middleware functions.
