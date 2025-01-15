# Product Store

This is an Angular project for a product store.

## Project Structure

```
/path/to/product-store/
├── node_modules
├── src
│   ├── app
│   │   ├── features
│   │   │   ├── create
│   │   │   ├── edit
│   │   │   ├── list
│   │   ├── shared
│   │   │   ├── components
│   │   │   │   ├── back-to-list
│   │   │   │   ├── form
│   │   │   │   ├── header
│   │   │   ├── interfaces
│   │   │   ├── resolvers
│   │   │   ├── services
│   │   ├── components
│   │   ├── services
│   │   ├── app.component.html
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   ├── assets
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
├── .editorconfig
│   .gitignore
├── angular.json
├── db.json
├── package-lock.json
├── package.json
├── proxy.config.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.spec.json

```

## Prerequisites

- Node.js
- Angular CLI

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hectorsalg/angular.git
   ```
2. Navigate to the project directory:
   ```bash
   cd /path/to/project/product-store
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Running the Project

To start the development server, run:

```bash
ng serve
```

Open your browser and go to `http://localhost:4200/`.

## Folder Structure

- **node_modules**: Project dependencies.
- **src**: Project source code.
  - **app**: Application components, models, and services.
  - **assets**: Static files.
  - **environments**: Environment configurations.
- **angular.json**: Angular CLI configurations.
- **package.json**: npm dependencies and scripts.
- **tsconfig.json**: TypeScript configurations.
- **proxy.config.json**: Proxy configurations.
- **db.json**: Database using json-server.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
