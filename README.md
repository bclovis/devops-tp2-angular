# Angular Hello World GitHub Pages

This project is a simple Angular application that displays a "Hello World" message. It is configured to be deployed on GitHub Pages.

## Project Structure

The project consists of the following files and directories:

- **README.md**: Documentation for the project.
- **package.json**: Configuration file for npm, listing dependencies and scripts.
- **angular.json**: Configuration settings for the Angular CLI.
- **tsconfig.json**: Main TypeScript configuration file.
- **tsconfig.app.json**: TypeScript configuration specific to the Angular application.
- **tsconfig.spec.json**: TypeScript configuration for the testing environment.
- **.editorconfig**: Defines coding styles for different editors.
- **.eslintrc.json**: Configuration for ESLint.
- **.prettierrc**: Configuration for Prettier.
- **.prettierignore**: Files and directories ignored by Prettier.
- **.gitignore**: Files and directories ignored by Git.
- **src/**: Contains the source code for the Angular application.
  - **main.ts**: Entry point of the application.
  - **index.html**: Main HTML file.
  - **styles.css**: Global styles.
  - **app/**: Contains the application module and components.
    - **app.module.ts**: Defines the root module.
    - **app.component.ts**: Exports the root component.
    - **app.component.html**: HTML template for the root component.
    - **app.component.css**: Styles for the root component.
  - **environments/**: Contains environment-specific settings.
    - **environment.ts**: Development settings.
    - **environment.prod.ts**: Production settings.
- **.github/**: Contains GitHub workflows.
  - **workflows/**: GitHub Actions workflows for CI and deployment.
    - **ci-lint.yml**: Workflow for continuous integration and linting.
    - **deploy.yml**: Workflow for deployment to GitHub Pages.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/angular-hello-world-ghpages.git
   cd angular-hello-world-ghpages
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the application**:
   ```bash
   ng serve
   ```
   Open your browser and navigate to `http://localhost:4200` to see the application in action.

## Usage

The application displays a simple "Hello World" message. You can modify the `app.component.html` file to change the content displayed.

## Deployment

This application is configured to be deployed to GitHub Pages. Upon merging a pull request, the GitHub Actions workflow will build the application and deploy it automatically.

## Contributing

Feel free to submit issues or pull requests to improve the application. Please ensure that your code adheres to the project's coding standards and passes the linter checks.