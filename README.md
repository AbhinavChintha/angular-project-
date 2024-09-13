# Angular Data Visualization App

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.4.

## Application Overview

This Angular application allows users to add datetime and temperature data with form validation. The data is visualized in real-time using Chart.js. The application contains two main features:
- **Add Data Tab**: Users can input datetime and temperature values with validation (datetime must be in the past and temperature must be between -50°C and 50°C).
- **View Data Tab**: Data is displayed on a line chart, plotting temperature against datetime.

## Development Server

Run `ng serve` to start a development server. Navigate to `http://localhost:4200/`. The application will automatically reload if you make any changes to the source files.

## Code Scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running Unit Tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running End-to-End Tests

Run `ng e2e` to execute end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Features

- **Angular Material**: Used for tab navigation and UI elements.
- **Reactive Forms**: Handles form validation for datetime and temperature inputs.
- **Chart.js**: Displays a real-time temperature chart based on input data.

## Project Structure
src/ │ ├── app/ │ ├── add-data/ │ │ ├── add-data.component.ts # Component for adding data with form validation │ │ ├── add-data.component.html # Template for data input form │ │ └── add-data.component.css # Styles for Add Data component │ │ │ ├── view-data/ │ │ ├── view-data.component.ts # Component for visualizing data using Chart.js │ │ ├── view-data.component.html # Template for the temperature chart │ │ └── view-data.component.css # Styles for View Data component │ │ │ ├── app.component.ts # Main app component │ └── app.module.ts # Main app module, sets up routing and components │ └── environments/ # Environment settings (dev/prod)


## How to Use the Application

1. Navigate to the **Add Data** tab to input datetime and temperature values.
2. Form validation ensures the datetime must be in the past and the temperature between -50°C and 50°C.
3. The **View Data** tab will display the entered data as a temperature vs. datetime line chart in real-time.

## Further Help

To get more help on the Angular CLI use `ng help` or check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## License

This project is licensed under the MIT License.
