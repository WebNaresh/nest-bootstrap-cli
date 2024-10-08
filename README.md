# nest-bootstrap-cli

A simple CLI tool to bootstrap a NestJS project with TypeORM and Swagger.

## Features

- **NestJS**: A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.
- **TypeORM**: An ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms.
- **Swagger**: A tool to generate API documentation and provide a user interface to interact with the API.

## Installation

To install the CLI tool, run:

```bash
npm install -g nest-bootstrap-cli
```

## Usage

To create a new NestJS project with TypeORM and Swagger, run:

```bash
nest-bootstrap-cli new <project-name>
```

Replace `<project-name>` with the desired name of your project.

## Commands

- `new <project-name>`: Creates a new NestJS project with TypeORM and Swagger.
- `generate <resource>`: Generates a new resource (e.g., module, service, controller).

## Example

```bash
nest-bootstrap-cli new my-nestjs-app
cd my-nestjs-app
npm run start
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
